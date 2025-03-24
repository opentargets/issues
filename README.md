# Open Targets Platform & Open Targets Genetics
This repo is the **issue tracker** for the Open Targets Platform. **All issues across Open Targets Platform should be raised here!**

Do you have questions for us? Ask on [Open Targets Community](https://community.opentargets.org/)!

Additional metadata about tickets, roadmap and priorities is available via [GitHub projects (private)](https://github.com/orgs/opentargets/projects)

## Site
Go to the [Open Targets Platform site](https://platform.opentargets.org/).

## Documentation
Go to the [Open Targets Platform Documentation](https://platform-docs.opentargets.org/).

## Relevant Github repos

The Open Targets Platform code is distributed across several repos, the most relevant of which are:
* #### Data and evidence
  * [curation](https://github.com/opentargets/curation) — Open Targets curation repository
  * [evidence\_datasource\_parsers](https://github.com/opentargets/evidence_datasource_parsers) — internal pipelines used to generate evidence
  * [json\_schema](https://github.com/opentargets/json_schema) — evidence object schema used for evidence and association scoring
  * [OnToma](https://github.com/opentargets/OnToma) — Python module to map disease or phenotype terms to EFO

* #### Gentropy
  * [gentropy](https://github.com/opentargets/gentropy) — Open Targets' genomics toolkit

* #### Orchestration
  * [orchestration](https://github.com/opentargets/orchestration) — Open Targets data pipelines orchestrator

* #### Backend API
  * [platform-api](https://github.com/opentargets/platform-api) — GraphQL API
  * [ot-ai-api](https://github.com/opentargets/ot-ai-api) — OpenAI API router

* #### Unified pipeline
  * [otter](https://github.com/opentargets/otter) — **O**pen **T**argets' **T**ask **E**xecuto**R** i.e. scripts that process and prepare data for our ETL pipelines
  * [platform-etl-backend](https://github.com/opentargets/platform-etl-backend): ETL pipelines to generate associations, evidence, and entity indices
  * [platform-etl-openfda-faers](https://github.com/opentargets/platform-etl-openfda-faers): ETL pipeline to process Open FDA adverse events data
  * [platform-etl-literature](https://github.com/opentargets/platform-etl-literature): ETL pipeline to generate similar entities and publications
  * [platform-output-support](https://github.com/opentargets/platform-output-support): scripts for infrastructure tasks and generating a Platform release

* #### Deployment
  * [terraform-google-opentargets](https://github.com/opentargets/terraform-google-opentargets-platform) — Open Targets Infrastructure definition, scripts in charge of setting up the data layer with the relevant disk images and spinning up the rest of the infrastructure.

* #### Frontend
  * [ot-ui-apps](https://github.com/opentargets/ot-ui-apps) — Open Targets web applications


## Copyright

Copyright 2014-2025 EMBL - European Bioinformatics Institute, Genentech, GSK,
MSD, Pfizer, Sanofi and Wellcome Sanger Institute

This software was developed as part of the Open Targets project. For more
information please see: http://www.opentargets.org

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy of the
License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
