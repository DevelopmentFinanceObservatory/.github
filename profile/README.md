# Development Finance Observatory

**A shared, open platform for development finance data.** [Website](https://developmentfinance.org)

The Development Finance Observatory brings together data on aid, debt, health finance, domestic public finance and remittances, making it easier to find, connect, understand, and use.

The DFO is an initiative of [ONE Data](https://data.one.org/).

> [!Note]
> The Development Finance Observatory is currently under development and is expected to launch in late 2026.

## Why we are building it

Every year, billions of dollars move across borders through aid, loans, investment, remittances, and other financial flows.

These resources shape whether countries can build infrastructure, respond to crises, deliver healthcare, manage debt, and invest in long-term development.

The data needed to understand those flows already exists. Institutions including the OECD, World Bank, IMF, national governments, and multilateral organisations publish decades of carefully maintained statistics, reporting standards, and methodologies.

But the data remains fragmented across separate systems, incompatible formats, different classifications, and uneven update cycles. Researchers, governments, journalists, and civil society organisations repeatedly spend time finding, downloading, cleaning, reconciling, and interpreting the same sources.

When the data is difficult to use, important decisions are more likely to be driven by partial evidence or anecdote.

## What the DFO does

The Development Finance Observatory is designed to reduce that fragmentation and friction. It connects and builds on the work of the institutions that produce development finance data.

The DFO builds on [Google Data Commons](https://datacommons.org), extending its open knowledge graph and data model to the specifics of development finance.

## Who it is for

### Researchers and analysts

Start with clean, structured, and clearly sourced data. Spend less time reconciling conflicting figures and more time investigating trends, testing assumptions, and producing analysis.

### Journalists and policy advisers

Move from a difficult question to a credible answer more quickly. Find a number with a clear source, generate a chart that can be cited, and understand the methodology behind it.

### Government officials and planners

Track the financial flows affecting a country's fiscal and development position. Understand what has been committed, what has been disbursed, how financing is changing, and where gaps remain.

### Developers and institutional partners

Build on open data, APIs, shared schemas, and reusable components, without reconstructing the same underlying data infrastructure.

## Repositories

This GitHub organisation hosts the open-source components of the Development Finance Observatory.

| Repository                                                                | What it holds                                                                                                                                                          |
| ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`ai`](https://github.com/DevelopmentFinanceObservatory/ai)               | The agent harness and the MCP servers that let an AI assistant search, retrieve and analyse DFO data, deployed as one Cloud Run service.                               |
| [`apis`](https://github.com/DevelopmentFinanceObservatory/apis)           | The Search, Datasets, Graph, Presentation and Skills APIs, which turn natural-language questions into data specifications and serve datasets from the knowledge graph. |
| [`dcp`](https://github.com/DevelopmentFinanceObservatory/dcp)             | The Data Commons Platform, ONE Data's fork of Data Commons that serves the DFO knowledge graph.                                                                        |
| [`docs`](https://github.com/DevelopmentFinanceObservatory/docs)           | The build that gathers documentation from the DFO repositories into one published corpus.                                                                              |
| [`infra`](https://github.com/DevelopmentFinanceObservatory/infra)         | Terraform for the DFO's Google Cloud infrastructure.                                                                                                                   |
| [`ontology`](https://github.com/DevelopmentFinanceObservatory/ontology)   | The compiler that turns the DFO ontology, maintained in Wikibase, into Data Commons schema.                                                                            |
| [`pipelines`](https://github.com/DevelopmentFinanceObservatory/pipelines) | Dagster and dbt pipelines that download source data, standardise it and ingest it into the knowledge graph.                                                            |
| [`skills`](https://github.com/DevelopmentFinanceObservatory/skills)       | Agent Skills that give an AI assistant the methods, definitions and dataset caveats of a development-finance analyst.                                                  |
| [`spec-kit`](https://github.com/DevelopmentFinanceObservatory/spec-kit)   | The shared contracts for dataset specifications, frames, components and provenance, as Python packages.                                                                |
| [`website`](https://github.com/DevelopmentFinanceObservatory/website)     | The public Next.js site, which also proxies API traffic to the platform.                                                                                               |

Individual repositories document their own maturity, licensing, contribution process, and deployment status.

## Development status

The Development Finance Observatory is under active development.

Repositories may initially contain experimental interfaces, provisional schemas, incomplete documentation, or breaking changes. Stable components will be identified clearly as they mature.

The public platform is expected to launch in late 2026.

## Get involved

The DFO is being built for people working in government, research, journalism, civil society, technology, and development finance institutions.

You can:

- follow this organisation for new repositories and releases;
- [sign up for updates](https://developmentfinance.org);
- [contact the DFO team](mailto:data@one.org) about data, research, or institutional partnerships.

## Partners and support

The Development Finance Observatory is an initiative of [ONE Data](https://data.one.org/), developed with support from The Rockefeller Foundation, through its public charity RF Catalytic Capital, and Google.org. It is built in partnership with [Google Data Commons](https://datacommons.org).
