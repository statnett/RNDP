# S.W.A.M.P (p-SWAMP)

**P**ower **S**tability **W**ide **a**rea **M**onitoring and **P**rotection

The project aims to improve the reliability and efficiency of the Nordic power system through application development and by clarifying the prerequisites and requirements for a Nordic Wide Area Monitoring System (WAMS) and Wide Area Monitoring, Protection, and Control (WAMPAC). These systems use high-resolution, synchronized current and voltage measurements from phasor measurement units (PMUs).

## Open-Source Repository

The project is a Linux Foundation Energy hosted open source project. More information is available in [p-swamp/p-SWAMP: Python repository for the p-SWAMP project](https://github.com/p-swamp/p-SWAMP).

## Data Sources and Volume

The project uses PMU data. The source material gives the following estimates:

- Approximately 2,600 measurement points/channels.
- Approximately 4 MB per channel per five minutes.
- A maximum of 121.9 GB per hour if all measurement points deliver data.
- Approximately 1.3 million files per month.
- An estimated total dataset size of approximately 23 TB by the end of 2024.
- Five minutes of measurements per file.

The source includes a tentative CSV reference, but the file-format details need confirmation.

## Potential Project Tasks

The following tasks have been discussed as targets for S.W.A.M.P:

- Import PMU data.
- Identify the events found in the NewEPS project, as defined by the code in [SINTEF's NewEPS repository](https://gitlab.statnett.no/pmu-system/sintef-neweps).
- Define a message queue, potentially using Kafka, so that the application can emulate the production environment.
- Develop an application for operations that brings the different identified elements of NewEPS together in one system, following development best practices and using open-source graphical user interface (GUI) tools.
- Develop a machine learning (ML) model based on PMU data to advise operators using previously recorded events.

Future ML research topics include identifying different contingencies, clustering, and preventive measures versus event handling.



[Back to the project index](README.md)