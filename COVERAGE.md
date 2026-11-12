# Coverage

What this repository holds, built on 2026-11-11 from the legislation.gov.uk bulk data (Best Collection XML, Legislative Amendments, "Legislation on Website" list) plus the site itself for the few laws the bulk data lacks.

## Laws with text

One Markdown file per law; laws with 100 or more sections are a folder with one file per section. The status says how far the text can be trusted:

- **revised**: the current text, with all known changes applied.
- **revised-with-pending-changes**: the current text, but some changes are not yet applied; every file says so at the top.
- **as-enacted**: the text as originally made; it may have been changed since.
- **repealed**: no longer in force as a whole.

## Laws without text: the catalogue

Documents that legislation.gov.uk lists but holds only as a scanned PDF or as a record are in `catalogue/<type>/<year>.csv`, with a link to the source. Their PDFs are not copied here.

## Counts by type

| type | folder | revised | revised-with-pending-changes | as-enacted | repealed | catalogue only |
|---|---|---|---|---|---|---|
| `ukpga` | uk-parliament/acts/public | 2540 | 914 | 87 | 853 | 13169 |
| `ukla` | uk-parliament/acts/local | 16 | 0 | 182 | 1 | 19972 |
| `ukppa` | uk-parliament/acts/private | 0 | 0 | 0 | 0 | 869 |
| `ukcm` | uk-parliament/church-measures | 101 | 28 | 0 | 28 | 87 |
| `ukci` | uk-parliament/church-instruments | 0 | 0 | 60 | 0 | 0 |
| `uksi` | uk-parliament/regulations | 5193 | 876 | 50439 | 4127 | 48827 |
| `uksro` | uk-parliament/regulations | 0 | 0 | 0 | 0 | 307 |
| `ukmo` | uk-parliament/regulations | 0 | 0 | 1 | 0 | 124 |
| `asp` | scotland/acts | 275 | 110 | 0 | 17 | 0 |
| `ssi` | scotland/regulations | 948 | 172 | 6499 | 1124 | 2754 |
| `anaw` | wales/acts | 26 | 16 | 0 | 2 | 0 |
| `asc` | wales/acts | 18 | 15 | 0 | 1 | 0 |
| `mwa` | wales/measures | 13 | 6 | 0 | 3 | 0 |
| `wsi` | wales/regulations | 710 | 96 | 3065 | 806 | 2106 |
| `nia` | northern-ireland/acts | 167 | 35 | 11 | 26 | 0 |
| `nisr` | northern-ireland/regulations | 1894 | 373 | 5071 | 2039 | 9184 |
| `nisro` | northern-ireland/regulations | 0 | 0 | 1 | 0 | 8791 |
| `nisi` | northern-ireland/orders-in-council | 296 | 160 | 61 | 41 | 133 |
| `aep` | historic/england | 66 | 0 | 586 | 13 | 28 |
| `aosp` | historic/scotland | 80 | 5 | 0 | 24 | 0 |
| `aip` | historic/ireland | 10 | 0 | 0 | 1 | 35 |
| `apgb` | historic/great-britain | 32 | 4 | 0 | 22 | 2160 |
| `gbla` | historic/great-britain/local | 0 | 0 | 0 | 0 | 273 |
| `apni` | historic/northern-ireland-parliament | 258 | 17 | 0 | 12 | 1 |
| `mnia` | historic/northern-ireland-assembly | 2 | 0 | 0 | 0 | 0 |
| `eur` | eu-origin/regulations | 18273 | 1548 | 0 | 4671 | 100363 |
| `eudn` | eu-origin/decisions | 9620 | 552 | 1 | 3000 | 17577 |
| `eudr` | eu-origin/directives | 1185 | 137 | 0 | 713 | 2133 |
| `eut` | eu-origin/treaties | 5 | 0 | 0 | 0 | 0 |
| `ukmd` | (catalogue only) | 0 | 0 | 0 | 0 | 1 |
| **total** |  | **41728** | **5064** | **66064** | **17524** | **228894** |

## Known conversion gaps

Every law is checked word by word against its source. 138 laws lose 997 words between them, mostly symbols with subscripts, numbering such as `18ter` and technical tables. The list, with the missing words, is in `catalogue/conversion-gaps.jsonl`. No law failed to convert.

## Not included

- Explanatory notes, impact assessments and draft legislation.
- Welsh-language versions of bilingual texts.
- Court judgments.
- Past versions of each law (only the current text, for now).
