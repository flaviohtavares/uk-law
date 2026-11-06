# Instructions for AI agents

This repository holds the legislation of the United Kingdom as Markdown, converted from
legislation.gov.uk. It is **not an official source and not legal advice**. When you answer from it:

- quote the law's title and section, and give its `source_url` (the official page);
- say how current the text is (`text_date`) and warn when `status` is not `revised`;
- tell the user to check legislation.gov.uk, or a lawyer, before relying on it.

## Find a law: use the index, do not walk the folders

There are about 130,000 laws in over 400,000 files. Do not list or glob the folders. Search
[`index/laws.csv`](index/laws.csv) instead, one row per law:

| column | meaning |
|---|---|
| `id` | legislation.gov.uk id, e.g. `ukpga/2018/12` (Data Protection Act 2018) |
| `type` | id prefix, see the table below |
| `year`, `number` | year and number of the law (old Acts use regnal years in the id) |
| `title` | short title |
| `status` | see "Status" below |
| `extent` | where it applies: `E` England, `W` Wales, `S` Scotland, `N.I.` Northern Ireland |
| `topics` | official subject headings, for regulations and the Acts most of them are made under |
| `path` | the file to open |

Examples:

```sh
grep -i "data protection act" index/laws.csv
grep -i ",revised" index/laws.csv | grep -i "employment rights"
grep "^ukpga/1996/18," index/laws.csv
```

Titles of regulations usually start with "The" and end with the year. Many laws amend other
laws: an Act's own text already includes the amendments made to it when `status` is `revised`.

## Reading a law

- `path` ending in `.md`: the whole law is in that file.
- `path` ending in `/README.md`: a long law (100 sections or more) split into one file per section
  or schedule. The README has the front matter, the introductory text and a **Contents** list
  linking every part, e.g. `part-2/section-5.md`, `schedule-1.md`. Read the contents first and open
  only the sections you need.
- Every file starts with YAML front matter: `title`, `id`, `status`, `made_date`, `text_date`,
  `extent`, `source_url`, `pdf_urls`, `pending_changes`, `repealed_on`.
- Footnotes (`[^c-…]`, `[^f…]`, `[^M_…]`) are defined at the end of each file. Each starts with its
  kind, such as "Textual amendment:", "Commencement:" or "Modification:", and links the law that
  made the change. They explain where wording was inserted, substituted or omitted.

## Status

| status | meaning |
|---|---|
| `revised` | kept up to date by legislation.gov.uk editors |
| `revised-with-pending-changes` | revised, but some changes are not yet applied; `pending_changes` counts them |
| `as-enacted` | the text as originally made; later changes are **not** applied |
| `repealed` | no longer in force; kept for reference |

## Other ways in

- [`topics/README.md`](topics/README.md): laws in force by subject (employment, housing, tax...).
- [`nations/`](nations/): laws in force made by each nation's legislature.
- [`catalogue/`](catalogue/): laws that exist only as a PDF or a record, one CSV per type and year.
- [`COVERAGE.md`](COVERAGE.md): what is here and what is missing.

## Types

| id prefix | what | folder |
|---|---|---|
| `ukpga` | UK Public General Acts | `uk-parliament/acts/public/` |
| `ukla` | UK Local Acts | `uk-parliament/acts/local/` |
| `ukcm` | Church of England Measures | `uk-parliament/church-measures/` |
| `ukci` | Church Instruments | `uk-parliament/church-instruments/` |
| `uksi` | UK Statutory Instruments (regulations, orders, rules) | `uk-parliament/regulations/` |
| `asp` | Acts of the Scottish Parliament | `scotland/acts/` |
| `ssi` | Scottish Statutory Instruments | `scotland/regulations/` |
| `asc` | Acts of Senedd Cymru | `wales/acts/` |
| `anaw` | Acts of the National Assembly for Wales | `wales/acts/` |
| `mwa` | Measures of the National Assembly for Wales | `wales/measures/` |
| `wsi` | Wales Statutory Instruments | `wales/regulations/` |
| `nia` | Acts of the Northern Ireland Assembly | `northern-ireland/acts/` |
| `nisr` | Northern Ireland Statutory Rules | `northern-ireland/regulations/` |
| `nisi` | Northern Ireland Orders in Council | `northern-ireland/orders-in-council/` |
| `aep` | Acts of the Parliament of England (before 1707) | `historic/england/` |
| `aosp` | Acts of the old Parliament of Scotland (before 1707) | `historic/scotland/` |
| `aip` | Acts of the old Parliament of Ireland | `historic/ireland/` |
| `apgb` | Acts of the Parliament of Great Britain (1707 to 1800) | `historic/great-britain/` |
| `apni` | Acts of the Parliament of Northern Ireland (1921 to 1972) | `historic/northern-ireland-parliament/` |
| `mnia` | Measures of the Northern Ireland Assembly (1974) | `historic/northern-ireland-assembly/` |
| `eur` | EU-origin regulations | `eu-origin/regulations/` |
| `eudn` | EU-origin decisions | `eu-origin/decisions/` |
| `eudr` | EU-origin directives | `eu-origin/directives/` |
| `eut` | EU treaties | `eu-origin/treaties/` |

## Without cloning

Any file can be read directly at `https://raw.githubusercontent.com/flaviohtavares/uk-law/main/<path>`, for example
`https://raw.githubusercontent.com/flaviohtavares/uk-law/main/index/laws.csv`. To clone only part of the repository:

```sh
git clone --depth 1 --filter=blob:none --sparse https://github.com/flaviohtavares/uk-law
cd uk-law && git sparse-checkout set index topics uk-parliament/acts
```

The repository is updated every day from the legislation.gov.uk publication log.
