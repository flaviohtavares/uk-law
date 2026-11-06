# UK Law

The legislation of the United Kingdom as plain text: Acts and regulations of the UK Parliament,
Scotland, Wales and Northern Ireland, older Acts of the historic parliaments, and the EU-origin
legislation published on legislation.gov.uk.

> **Not an official source and not legal advice.** This is an independent copy made from
> legislation.gov.uk. Texts can be out of date or contain conversion errors. Always check the
> official text at [legislation.gov.uk](https://www.legislation.gov.uk) before relying on it.

## Where do you live?

[England](nations/england.md) · [Scotland](nations/scotland.md) · [Wales](nations/wales.md) ·
[Northern Ireland](nations/northern-ireland.md)

Each page lists the laws in force made for that nation. Laws of the UK Parliament can also
extend there; every file says where it extends.

## Looking for a subject?

[Topics](topics/README.md) lists the laws in force by subject, such as employment, housing, tax or
road traffic, using the subject headings of legislation.gov.uk.

## Using it with AI tools

The repository is laid out for AI assistants as well as people. [`index/laws.csv`](index/laws.csv)
has one row per law with the path of its file, and [AGENTS.md](AGENTS.md) explains the layout.

- **Claude Code:** install the plugin, then ask about UK law in any session:
  ```
  /plugin marketplace add flaviohtavares/uk-law-tools
  /plugin install uk-law@uk-law-tools
  ```
- **Codex and other agents:** install the same skill, or clone part of this repository and work
  inside it. Step-by-step instructions: [uk-law-tools](https://github.com/flaviohtavares/uk-law-tools).
- **ChatGPT, Claude.ai and any MCP client:** connect the free MCP server
  `https://uk-law-mcp.uk-law-mcp.workers.dev/mcp` (no sign-in). How to add it in each app:
  [uk-law-mcp](https://github.com/flaviohtavares/uk-law-mcp).
- **Any chat assistant that reads the web:** give it the link to [`llms.txt`](llms.txt) or to a law's
  file. Files can be read at `https://raw.githubusercontent.com/flaviohtavares/uk-law/main/<path>`.

The full clone is about 4 GB. To get only part of it:

```
git clone --depth 1 --filter=blob:none --sparse https://github.com/flaviohtavares/uk-law
cd uk-law && git sparse-checkout set index topics uk-parliament/acts
```

## Where things are

- `uk-parliament/`: Acts and regulations of the UK Parliament
- `scotland/`, `wales/`, `northern-ireland/`: devolved legislation
- `historic/`: parliaments that no longer exist (England, Great Britain, Scotland and Ireland before
  the unions, Northern Ireland before 1972)
- `eu-origin/`: EU-origin legislation as published by legislation.gov.uk
- `catalogue/`: documents that exist only as a PDF or a record, with links
- `index/laws.csv`: every law with text, one row each, with the path of its file
- `topics/`, `nations/`: laws in force by subject and by nation

Each file starts with the title, the status of the text, its date, its extent and a link to the
official version. [COVERAGE.md](COVERAGE.md) says what is here and what is missing.

## Licence

© Crown and database right. Derived from content available under the
[Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
from legislation.gov.uk. See [LICENSE.md](LICENSE.md).

## Who maintains this

Built and maintained by **[Tavlabs Ltd](https://www.tavlabs.uk/?utm_source=github&utm_medium=uk-law)**,
a London software house for small and medium businesses. We build data pipelines like this one, and
custom software for operations, from food safety to logistics. Need something similar?
[contact@tavlabs.uk](mailto:contact@tavlabs.uk)

This is an independent project. It is not affiliated with or endorsed by The National Archives,
legislation.gov.uk or the UK Government.
