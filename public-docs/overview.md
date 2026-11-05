# 1. What is the purpose of RNDP — the Research Platform?

*Research and Development (R&D) established RNDP to collaborate with external researchers. R&D aims to carry out projects that give external partners access to Statnett's data within the scope of individual R&D projects. The Research Platform has no datasets of its own. However, data can be made available on the platform so that project participants can access it through established R&D projects.*

*The platform was established in 2024 as a proof of concept on Azure Landing Zone. The project's goal was to create a scalable collaboration platform modeled on CERN's approach, but adapted to Statnett's Azure-first strategy and R&D's need to store large volumes of data.*

![CERN logo](https://upload.wikimedia.org/wikipedia/en/thumb/a/ae/CERN_logo.svg/160px-CERN_logo.svg.png)

## Goals for RNDP

- Access for external and internal users.
- The ability to securely make large volumes of data available and store them.
- Support for all forms of data analysis.
- Scalable and dynamic compute support.
- Support for dynamic and reactive data visualization.
- Cloud-agnostic and open source.
- Flexible, cost-effective storage options with different storage tiers.

## Can my project use the platform?

If your research project needs to share data with external partners, analyze data, or develop software in collaboration with external partners, RNDP may be the right solution. Contact our system owner at [kjell.myhren@statnett.no](mailto:kjell.myhren@statnett.no) to find out whether your project can get access. Getting access to try out the platform is straightforward.

## What are the mandatory requirements?

1. Your project participants must have either a Statnett user account or an Entra ID identity that we can federate. Most organizations meet this requirement.

## Projects on the platform

See the [project index](projects/README.md) for individual project pages.


- [Project - Talk2PowerSystem](projects/talk2powersystem.md)
- [Project - S.W.A.M.P](projects/p-swamp.md)

## What RNDP currently offers projects

- Secure login through JupyterHub for users with Statnett or external (federated) Entra ID identities.
- Data storage for the lifetime of the project, supporting confidentiality levels up to K1 (K3 is planned).
- More cost-effective storage options, with cold storage available on request.
- Personal and shared storage areas for all project participants.
- Backups of all user and project data by default.
- A choice of notebook environments with 1–6 CPUs and 4–24 GB of memory. Additional configurations can be offered on request.
- Support for launching and managing your own pods, with the freedom to define them in Kubernetes.
- GPU access, with several options available. Contact us if you have specific requirements.
- PostgreSQL and GraphDB are available now. A time-series database is under consideration, and other databases can be made available on request.
- Freedom to use any programming languages and libraries.
- Code scanning on the platform.
- Ubuntu in the default notebook environment. Other operating systems can be made available on request, provided they are open source.
- Help setting up and testing proprietary software, as we have previously done with [GraphQL](https://rndpsvc.statnett.no/graphdb/login).
- Help and support for projects on the platform to make onboarding new projects as straightforward as possible.
- Ongoing expansion and development of RNDP, with new functionality added regularly.

Get in touch if you would like to know whether we can support your project!