# Council Data Project

A search engine for local government.

We aim to empower journalists, activists, and community members in
following council action by combining and simplifying sources of
information on municipal council meetings and actions.

More information on us and links to all of the municipalities we serve
are available on [councildataproject.org](https://councildataproject.org).

If you are interested in contributing in any way (development, design, project management, community management, etc.) let us know via GitHub issue.

## Libraries

| Repo    | Details | Build Status                                                                                                                                                                                                       |
| ----------- |--------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [cookiecutter-cdp-deployment](https://github.com/CouncilDataProject/cookiecutter-cdp-deployment)     | Start here if you want to deploy Council Data Project! | [![Build Example Repo](https://github.com/CouncilDataProject/cookiecutter-cdp-deployment/actions/workflows/build.yml/badge.svg)](https://github.com/CouncilDataProject/cookiecutter-cdp-deployment/actions/workflows/build.yml)         |
| [cdp-backend](https://github.com/CouncilDataProject/cdp-backend)     | Our single source for backend development for all deployments. Every deployment utilizes this library for processing and storing data. Written in Python. | [![CI](https://github.com/CouncilDataProject/cdp-backend/actions/workflows/ci.yml/badge.svg)](https://github.com/CouncilDataProject/cdp-backend/actions/workflows/ci.yml)         |
| [cdp-frontend](https://github.com/CouncilDataProject/cdp-frontend)     | Our single source for frontend development for all deployments. Every deployment utilizes this library for rendering it's web application. Written in TypeScript.| [![Build Main](https://github.com/CouncilDataProject/cdp-frontend/actions/workflows/build-main.yml/badge.svg)](https://github.com/CouncilDataProject/cdp-frontend/actions/workflows/build-main.yml)         |
| [cdp-scrapers](https://github.com/CouncilDataProject/cdp-scrapers)     | A library for legislative scrapers. Some work across multiple councils and some are specific to a single council. Written in Python. | [![CI](https://github.com/CouncilDataProject/cdp-scrapers/actions/workflows/ci.yml/badge.svg)](https://github.com/CouncilDataProject/cdp-scrapers/actions/workflows/ci.yml)         |
| [cdp-data](https://github.com/CouncilDataProject/cdp-data)     | Generalized functions for downloading, processing, and plotting data from any CDP deployment. Written in Python. | [![CI](https://github.com/CouncilDataProject/cdp-data/actions/workflows/ci.yml/badge.svg)](https://github.com/CouncilDataProject/cdp-data/actions/workflows/ci.yml)         |
| [speakerbox](https://github.com/CouncilDataProject/speakerbox)     | A library to assist with quickly annotating audio datasets, and training a model using that data for speaker identification. Written in Python. | [![Build](https://github.com/CouncilDataProject/speakerbox/actions/workflows/ci.yml/badge.svg)](https://github.com/CouncilDataProject/speakerbox/actions/workflows/ci.yml)         |

## In Development

| Repo    | Details |
|-------- |-------- |
| [semantic-navigator](https://github.com/CouncilDataProject/semantic-navigator) | An active learning approach for user driven archival search. Written in Python. |
| [transcript-file-format](https://github.com/CouncilDataProject/transcript-file-format) | A possible future for a transcript model that many projects can share. |


## Deployments

| Deployment    | Event Gather Status                                                                                                                                                                                                       |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Seattle](https://github.com/CouncilDataProject/seattle)     | [![Event Gather](https://github.com/CouncilDataProject/seattle/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/seattle/actions/workflows/event-gather-pipeline.yml)         |
| [King County](https://github.com/CouncilDataProject/king-county) | [![Event Gather](https://github.com/CouncilDataProject/king-county/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/king-county/actions/workflows/event-gather-pipeline.yml) |
| [Portland](https://github.com/CouncilDataProject/portland)    | [![Event Gather](https://github.com/CouncilDataProject/portland/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/portland/actions/workflows/event-gather-pipeline.yml)       |
| [Denver](https://github.com/CouncilDataProject/denver)      | [![Event Gather](https://github.com/CouncilDataProject/denver/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/denver/actions/workflows/event-gather-pipeline.yml)           |
| [Alameda](https://github.com/CouncilDataProject/alameda)     | [![Event Gather](https://github.com/CouncilDataProject/alameda/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/alameda/actions/workflows/event-gather-pipeline.yml)         |
| [Oakland](https://github.com/CouncilDataProject/oakland)      | [![Event Gather](https://github.com/CouncilDataProject/oakland/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/oakland/actions/workflows/event-gather-pipeline.yml)         |
| [Charlotte](https://github.com/CouncilDataProject/charlotte)      | [![Event Gather](https://github.com/CouncilDataProject/charlotte/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/charlotte/actions/workflows/event-gather-pipeline.yml)         |
| [San Jose](https://github.com/CouncilDataProject/san-jose)      | [![Event Gather](https://github.com/CouncilDataProject/san-jose/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/san-jose/actions/workflows/event-gather-pipeline.yml)         |
| [Mountain View](https://github.com/CouncilDataProject/mountain-view)      | [![Event Gather](https://github.com/CouncilDataProject/mountain-view/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/mountain-view/actions/workflows/event-gather-pipeline.yml)         |
| [Louisville](https://github.com/CouncilDataProject/louisville)      | [![Event Gather](https://github.com/CouncilDataProject/louisville/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/louisville/actions/workflows/event-gather-pipeline.yml)         |
| [Menifee](https://github.com/CouncilDataProject/city-of-menifee)      | [![Event Gather](https://github.com/CouncilDataProject/city-of-menifee/actions/workflows/event-gather-pipeline.yml/badge.svg)](https://github.com/CouncilDataProject/city-of-menifee/actions/workflows/event-gather-pipeline.yml)         |

## Deployments Maintained By Others

* [Asheville](https://github.com/sunshine-request/cdp-asheville)
* [Montana State Legislature](https://github.com/OpenMontana/montana-legislature-council-data-project)
* [Missoula](https://github.com/OpenMontana/missoula-council-data-project)


## Inactive Deployments (In Need of A Maintainer)

* [Milwaukee](https://github.com/CouncilDataProject/milwaukee)
* [Boston](https://github.com/CouncilDataProject/boston)
* [Richmond](https://github.com/CouncilDataProject/richmond)
* [Atlanta](https://github.com/CouncilDataProject/atlanta)
* [Long Beach](https://github.com/CouncilDataProject/long-beach)
* [Albuquerque](https://github.com/CouncilDataProject/albuquerque)
* [Pittsburgh](https://github.com/CouncilDataProject/pittsburgh-pa)
