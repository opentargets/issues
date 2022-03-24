# Open Targets Platform & Open Targets Genetics
This repo is the **issue tracker** for the Open Targets Platform and Open Targets Genetics projects. **All issues should be raised here.**

Additional metadata about tickets, roadmap and priorities is available via [Zenhub](https://www.zenhub.com)

## Site
Go to the [Open Targets Platform site](https://platform.opentargets.org/).
Go to the [Open Targets Genetics site](https://genetics.opentargets.org/).

## Docs
Go to the [Open Targets Platform docs](https://platform-docs.opentargets.org/).
Go to the [Open Targets Genetics docs](https://genetics-docs.opentargets.org/).

## Other relevant repos
Platform
The project code is distributed across several repos, the most relevant of which are:
* [platform-app](https://github.com/opentargets/platform-app): the front-end app
* [GraphQL api](https://github.com/opentargets/platform-api-beta): the GraphQL api (used by platform-app, but can also be used independently; [docs](https://platform-docs.opentargets.org/data-access/graphql-api))
* [docs](https://platform-docs.opentargets.org/infrastructure): the pipeline to generate the OT data

Genetics
The project code is distributed across several repos, the most relevant of which are:
* [genetics-app](https://github.com/opentargets/genetics-app): the front-end UI app
* [genetics-api](https://github.com/opentargets/genetics-api): the graphql api
* [V2G](https://github.com/opentargets/g2v_data): Variant to gene data including tissues and cell-lines
* [V2D](https://github.com/opentargets/v2d_data): Variant to disease data
* [genetics-pipe](https://github.com/opentargets/genetics-pipe): the data pipeline
* [genetics-backend](https://github.com/opentargets/genetics-backend): scripts to load the data into clickhouse
* [genetics-sumstat-data](https://github.com/opentargets/genetics-sumstat-data): workflows for processing summary statistics files
* [genetics-variant-annotation](https://github.com/opentargets/genetics-variant-annotation): workflow to produce variant index annotation
* [genetics-finemapping](https://github.com/opentargets/genetics-finemapping): repo of the fine-mapping pipeline
* [terraform-google-genetics-portal](https://github.com/opentargets/terraform-google-genetics-portal): repo for Genetics Portal deployment
