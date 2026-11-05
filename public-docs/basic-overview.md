# Basic Platform Overview

## Platform design

The RNDP platform was built for research and collaboration. We have chosen open-source solutions wherever possible, within the limits of Statnett policy. The platform is inspired by the data collaboration platform built by [CERN](https://home.cern/).

We have planned for a possible exit from Azure. Although switching cloud providers becomes increasingly difficult over time, a move away from Azure should still be relatively straightforward.

## Data storage and access

All data on RNDP is stored only once, with users granted read permissions through their project membership. Avoiding duplicate storage keeps costs as low as possible while giving research projects the access they need to deliver results.

## Project-specific containers

When setting up a new project, the RNDP team works with the project to define a selection of containers. These offer different CPU and GPU configurations and capabilities, as well as software relevant to the project.

## Resources on demand

Project participants can choose from these containers when they log in. RNDP then provisions the requested resources. This allows each user to select the hardware best suited to each task, helping to keep costs down.

## Pausing and resuming work

To reduce costs, the platform pauses the container when the user stops working or logs off. The container retains its last-used state, allowing the user to resume work where they left off.