# Open Targets Platform
This repo is the issue tracker for the Open Targets Platform project. **All issues should be raised here.**

## Site
Go to the [Open Targets Platform site](https://www.targetvalidation.org/).

## Docs
Go to the [Open Targets Platform docs](https://docs.targetvalidation.org/).

## Other relevant repos
The project code is distributed across several repos, the most relevant of which are:
* [webapp](https://github.com/opentargets/webapp): the front-end angularjs app
* [rest_api](https://github.com/opentargets/rest_api): the rest api (used by webapp, but can also be used independently; [docs](http://api.opentargets.io/v3/platform/docs))
* [opentargets-py](https://github.com/opentargets/opentargets-py): a python client for the rest api
* [data-pipeline](https://github.com/opentargets/data_pipeline): the pipeline to generate the OT data

## Releases

Below is a list of the platform releases and the links to the respective version of each of the components that make up the plaform:

#### Release 19.02

- **Data pipeline code:** https://github.com/opentargets/data_pipeline/releases/tag/19.02.1
   ([docker image](http://quay.io/opentargets/mrtarget:19.02.1))
- **Data pipeline configuration for loading public data:** [mrtarget.data-2019-02-05.v3.yml](https://storage.googleapis.com/open-targets-data-releases/19.02/input/mrtarget.data-2019-02-05.v3.yml)
- **Data snapshot (alternative to data pipeline for loading public data)**: https://console.cloud.google.com/storage/browser/open-targets-data-releases/19.02/output/es_snapshot/
- **Rest API code:** https://github.com/opentargets/rest_api/releases/tag/19.02.1
   ([docker image](http://quay.io/opentargets/rest_api:19.02.1))
- **Web App code:** https://github.com/opentargets/webapp/releases/tag/3.11.2
   ([docker image](http://quay.io/opentargets/webapp:19.02.1))
