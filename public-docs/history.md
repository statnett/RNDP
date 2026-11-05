# A Brief History of the RNDP Platform

## 2024

Research and Development (R&D) contacted [Unicus/Auticon](https://auticon.com/no/) in May 2024 about building a research platform similar to the [CERN](https://opendata.cern.ch/) data platform. Following some initial research, Unicus/Auticon agreed to start building a proof of concept (PoC).

The RNDP requirements were:

- Support data analysis, primarily Python, but also R and other languages.
- Use open-source solutions, apart from being based on Azure.
- Support large datasets: 22 TB or more for the intended project.
- Grant external researchers access to the platform.
- Securely store K3 data.
- Make all this functionality available at a reasonable cost to R&D.

Over the first summer, Unicus/Auticon built RNDP as a PoC, incrementally adding functionality and meeting one goal after another. By late October, Unicus/Auticon had met all the requirements and provided an estimate of storage costs. With the initial goals reached, R&D decided that work should begin on a fully operational platform.

## 2025

After building over the winter, and with a few pivots in infrastructure setup and requirements, the platform opened to users on April 1, 2025.

By May 2025, Unicus/Auticon had invited the first project, Talk2PowerSystem, to use RNDP. Unicus/Auticon supported the project by adding support for users to start their own Kubernetes jobs.

In the autumn of 2025, Unicus/Auticon set up a GraphDB instance, a chatbot, and the platform's first GPUs. 

Toward the end of 2025, Unicus/Auticon began supporting the creation of user pods.

## 2026

In the early spring of 2026, Unicus/Auticon also brought the first K3 data onto the platform, and added mechanisms for MTM logging, and exfiltration logging/detection.

In early spring, Unicus/Auticon migrated RNDP to [Sweden Central](https://datacenters.microsoft.com/globe/explore?info=region_swedencentral), which offered a better selection of GPUs. Unicus/Auticon could now add both A10 and A100 GPUs alongside the older M60 GPUs that had been available since the previous autumn.

In late March, Unicus/Auticon began work on an alternative to Statnett Artifactory to obtain approval for using K3 data. 

By mid-May, Unicus/Auticon was ready to deploy Harbor, providing both image hosting and vulnerability scanning. As expected, Unicus/Auticon identified outdated packages and libraries and began updating them. 

By August, the platform also got a default time-series database in place, ClickHouse. At the same time, work started onboarding the p-SWAMP open source research project into the platform.