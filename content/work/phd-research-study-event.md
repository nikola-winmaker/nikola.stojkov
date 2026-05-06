+++
title = "PhD Research Study Event"
type = "work"
date = 2026-03-30
draft = false
+++

## Event Overview

The PhD research study event will be held on **10 May 2026**, with **gathering in front of the hotel at 12:30 PM** and the main program running from **1:00 PM to 7:00 PM** at the **Sheraton Hotel Novi Sad conference room**.

This session is designed for the research group to review study goals, align on workshop tasks, discuss the toolchain setup, and work through the planned study activities together.

> Lunch is organized at the hotel and all participants will receive thank you gifts at the end of the event.

{{< emphasis-note2 >}}Participants should be familiar with C Programming Language, basic understanding of SoC architecture, and familiarity with inter-processor communication concepts.{{< /emphasis-note2 >}}

## Venue

- **Location:** Sheraton Hotel Novi Sad, conference room
- **Date:** Sunday, 10 May 2026
- **Gathering in front of the hotel:** 12:30 PM
- **Main session:** 1:00 PM to 7:00 PM
- **Maps:** [Open in Google Maps](https://www.google.com/maps/search/Sheraton+Hotel+Novi+Sad/) or [Open in OpenStreetMap](https://www.openstreetmap.org/search?query=Sheraton%20Hotel%20Novi%20Sad)

{{< centered-cta-link "#setup-steps" "Registration" >}}

{{< emphasis-note >}}Please meet in front of the hotel at **12:30 PM** so the group can gather before moving into the conference room for the opening session.{{< /emphasis-note >}}

## Agenda

| Time | Activity |
| --- | --- |
| 12:30 PM - 12:50 PM | Gathering in front of the hotel and group arrival |
| 1:00 PM - 1:45 PM | Welcome and event introduction |
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
Please see [Toolchain installation](#setup-steps).


### Reading Materials

This section is reserved for preparation material that will be shared with the research group before the event.

- [HALO Presentation](/halo-reading-materials-switch.html)
- [HALO Papers](https://unsacrs-my.sharepoint.com/:f:/r/personal/stojkov_dp20_2022_uns_ac_rs/Documents/HALO/HaloPublications?csf=1&web=1&e=2AUtg3)
- [HALO API](https://nikola-winmaker.github.io/PhdHaloRSG/)
- [HALO Workshop](/system_specification.html)

## GIT Repo and Toolchain installation

{{< emphasis-note >}}Participants should prepare their laptops before the event so the hands-on session can start on time.{{< /emphasis-note >}}

Installation of the repository and tools requires approximately **15 GB** of free disk space.

Usage of Docker is necessary, and Docker Desktop can be used for free if you are:
- Individual / personal use
- Student

### Setup Steps

1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop/).
   1. Run Docker Desktop.
   2. Select `Personal` use, or skip the initial setup if needed.
2. Install [Visual Studio Code](https://code.visualstudio.com/).
   1. Install the [Docker extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker).
   2. Install the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).
   3. Install the [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree).
3. Clone the PhD Research Study repository from [GitHub](https://github.com/nikola-winmaker/PhdHaloRSG.git).
4. Open the repository in VS Code, then open a terminal in the repository root.
5. Run the following command:

   ```bash
   docker compose build dev
   ```

6. In VS Code, press `Ctrl+Shift+P` or on MAC OS `Cmd+Shift+P`, search for `Reopen in Container`, and run that command.
7. Inside the container, install the [Tasks extension](https://marketplace.visualstudio.com/items?itemName=actboy168.tasks) and [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
8. Click `Setup environment` in the VS Code bottom bar.

   Wait until all submodules and tools are fully installed.

9. From the bottom bar, click `Clean build all & Run` select `console` in the pop-up prompt on the top and then `Classical`.

You should see Linux boot in the console and messages in the form `[APPx]`, where `x` is `1`, `2`, `3`, and `4`.

{{< centered-cta-link "https://forms.office.com/r/2b0GsXpSwZ" "Register for the event" >}}

