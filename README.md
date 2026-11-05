# Statnett's Research and Development Platform (RNDP)

RNDP is a shared research environment where Statnett and external partners collaborate on research and development projects. It brings Statnett production datasets, analysis tools and computing resources together to support data exploration, analysis and software development in a secure environment.

Partners get access to Jupyter notebooks, shared storage and on-demand CPU and GPU resources, with support from the Statnett RNDP team to get started and tailor the environment to their needs.

## Platform Overview

Research and Development (R&D) established RNDP to collaborate with external researchers. R&D aims to carry out projects that give external partners access to Statnett's data within the scope of individual R&D projects. The Research Platform has no datasets of its own. However, data can be made available on the platform so that project participants can access it through established R&D projects.

The platform was established in 2024 as a proof of concept on Azure Landing Zone. The project's goal was to create a scalable collaboration platform modeled on CERN's approach, but adapted to Statnett's Azure-first strategy and R&D's need to store large volumes of data.

<img src="https://thumb.wikimedia.org/wikipedia/commons/thumb/f/f1/CERN_logo_badge.svg/250px-CERN_logo_badge.svg.png?utm_source=en.wikipedia.org&utm_campaign=parser&utm_content=thumbnail" alt="CERN logo" width="120">

## Goals for RNDP

- Access for internal and external (partner) users.
- The ability to securely make large volumes of data available and store them.
- Support for all forms of data analysis.
- Scalable and dynamic compute support.
- Support for dynamic and reactive data visualization.
- Cloud-agnostic and open source.
- Flexible, cost-effective storage options with different storage tiers.

## Can my project use the platform?

If your research project needs to share data with external partners, analyze data, or develop software in collaboration with external partners, RNDP may be the right solution. Contact our system owner at [kjell.myhren@statnett.no](mailto:kjell.myhren@statnett.no) to find out whether your project can get access. Getting access to try out the platform is straightforward.

## What are the mandatory requirements?

Your project participants must have either a Statnett user account or an Entra ID identity that we can federate. Most organizations meet this requirement.

## What RNDP currently offers projects

- Secure login through JupyterHub for users with Statnett or external (federated) Entra ID identities.
- Data storage for the lifetime of the project, supporting confidentiality levels up to K1 (K3 is planned).
- More cost-effective storage options, with cold storage available on request.
- Personal and shared storage areas for all project participants.
- Backups of all user and project data by default.
- A choice of notebook environments with 1–6 CPUs and 4–24 GB of memory. Additional configurations can be offered on request.
- Support for launching and managing your own pods, with the freedom to define them in Kubernetes.
- GPU access, with several options available. Contact us if you have specific requirements.
- PostgreSQL, ClickHouse and GraphDB are available now.Other databases can be made available on request.
- Freedom to use any programming languages and libraries.
- Code scanning on the platform.
- Ubuntu in the default notebook environment. Other operating systems can be made available on request, provided they are open source.
- Help setting up and testing proprietary software for your own project
- Help and support for projects on the platform to make onboarding new projects as straightforward as possible.
- Ongoing expansion and development of RNDP, with new functionality added regularly.

Get in touch if you would like to know whether we can support your project!

## Further documentation

### Platform documentation

- [Basic Platform Overview](docs/basic-overview.md)
- [A Brief History of the RNDP Platform](docs/history.md)
- [How to Get Access to the Research and Development Platform (RNDP)](docs/getting-access.md)

### Projects

- [Projects on RNDP](docs/projects/README.md)
	- [Talk2PowerSystem](docs/projects/talk2powersystem.md)
	- [S.W.A.M.P (p-SWAMP)](docs/projects/p-swamp.md)