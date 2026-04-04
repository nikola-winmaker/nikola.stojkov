+++
title = "PhD Research Study Event"
type = "work"
date = 2026-03-30
draft = false
+++

## Event Overview

The PhD research study event will be held on **10 May 2026**, with **gathering in front of the hotel at 12:30 PM** and the main program running from **1:00 PM to 6:00 PM** at the **Sheraton Hotel Novi Sad conference room**.

This session is designed for the research group to review study goals, align on workshop tasks, discuss the toolchain setup, and work through the planned study activities together.

> Lunch is organized at the hotel and all participants will receive thank you gifts at the end of the event.


## Venue

- **Location:** Sheraton Hotel Novi Sad, conference room
- **Date:** Sunday, 10 May 2026
- **Gathering in front of the hotel:** 12:30 PM
- **Main session:** 1:00 PM to 6:00 PM
- **Maps:** [Open in Google Maps](https://www.google.com/maps/search/Sheraton+Hotel+Novi+Sad/) or [Open in OpenStreetMap](https://www.openstreetmap.org/search?query=Sheraton%20Hotel%20Novi%20Sad)

{{< centered-cta-link "#toolchain-installation" "Registration" >}}

{{< emphasis-note >}}Please meet in front of the hotel at **12:30 PM** so the group can gather before moving into the conference room for the opening session.{{< /emphasis-note >}}

## Agenda

| Time | Activity |
| --- | --- |
| 12:30 PM - 12:50 PM | Gathering in front of the hotel and group arrival |
| 1:00 PM - 1:30 PM | Welcome and event introduction |
| 1:30 PM - 1:45 PM | Toolchain check and wrap-up discussion |
| 2:00 PM - 3:00 PM | Lunch break organized at the hotel
| 3:15 PM - 6:45 PM | Hands-on study session and wrap-up discussion |
| 6:45 PM - 7:00 PM | Thank you gifts and closing |

If you have dietary requirements, please include them in the registration form.

## Research Study Goals

The goal of the workshop is to compare how participants design communication architecture between partitions (AMPs)
in heterogeneous SoC using:

- a classical approach / AD-HOC methods
- the HALO framework approach (PhD deliverable)

{{< emphasis-note >}}During the hands-on work, participants should solve the same design problem in both approaches and record the same information for both, so the comparison stays consistent.{{< /emphasis-note >}}

### Working Hypotheses

- **H1:** HALO reduces development and integration time, measured in engineering effort and integration iterations, compared to traditional AMP development approaches.
- **H2:** HALO improves architectural clarity and maintainability, measured through artifact consistency and modification effort, compared to traditional design methods.
- **H3:** HALO enables portable and reusable architecture specifications, measured by the degree of reuse and required platform-specific adaptations.
- **H4:** The HALO framework improves architectural scalability and flexibility of inter-processor communication in AMP systems compared to existing IPC mechanisms.

### Study Task for Classical and HALO Approach

Participants will be asked to:

- design the communication architecture between AMPs in SoC
- define the same communication attributes in both approaches
- update the design when a change request is introduced
- compare how difficult it is to understand, modify, and maintain the solution

### What Participants Should Record

Participants should capture the same attributes for the **classical method** and for **HALO**:

Link to the surveys: 

- [Survey Classical method](https://forms.cloud.microsoft/r/5s1SzaBPJv)
- [Survey HALO Framework method](https://forms.cloud.microsoft/r/rL9RqVx3iB)

# Participant Prerequisites

### Laptop and Preparation

Laptop for the event is necessary! Please make sure you have administrator access so the required toolchain libraries can be installed.
Please see [Toolchain installation](#toolchain-installation).


### Reading Materials

This section is reserved for preparation material that will be shared with the research group before the event.

- [HALO Presentation](/halo-reading-materials-switch.html)
- [HALO Papers](https://unsacrs-my.sharepoint.com/:f:/r/personal/stojkov_dp20_2022_uns_ac_rs/Documents/HALO/HaloPublications?csf=1&web=1&e=2AUtg3)
- [Halo API](/_to_be_added_)

## GIT Repo and Toolchain installation

{{< emphasis-note >}}Participants should prepare their laptops before the event so the hands-on session can start on time.{{< /emphasis-note >}}

Instalation for repo and tools will require approximatelly 30GB of storage!

Ussage of Docker is nessesary but you can use Docker Desktop for free if you are:
- Individual / personal use
- Student

```bash
# Step 1: Install [Docker Desktop](https://www.docker.com/products/docker-desktop/)  and Install [VS Code](https://code.visualstudio.com/)
# Step 2: in VS Code install [Docler plugin](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

# Step 3: Clone repository for PhD Research Study from [here](https://github.com/nikola-winmaker/PhdHaloRSG.git)
# Step 4: Open repo in VS Code and then open terminal in root of repo
# Step 5: Run:   docker compose build dev
# Step 6: in VS Code run Ctrl+Shift+P then type "Reopen in Container"
# Step 7: Install Tasks plugin in Container
# Step 7: Open terminal and run bash /workspaces/PhdHaloRSG/tools/scripts/bootstrap_env.sh
# wait untill all submodules and tools are installed

# Step 8: Try "Clean build all & Run" from bottom bar 
# Step 9: Run "QEMU Sys Run" -> you should see linux boot and [APPx] where x is 1, 2, 3 and 4 shown on console

```

{{< centered-cta-link "https://forms.office.com/r/2b0GsXpSwZ" "Register for the event" >}}

