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

- **H1:** Using the HALO framework speeds up integration and development of AMP systems compared to the traditional approach.
- **H2:** Designing software architectures using the HALO framework gives better overview and maintainability compared to traditional methods.
- **H3:** The HALO framework provides portability and reuse of software architectural descriptions for different platforms with no or minimal effort.
- **H4:** The HALO framework gives better scalability and flexibility for IPC communication in AMP systems compared to already available solutions.

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


## Laptop and Preparation

Please let us know one of the following when registering:

- you need a laptop provided on site
- you will bring your own laptop

If you are bringing your own laptop, please also make sure you have administrator access so the required toolchain libraries can be installed.
Please see [Toolchain installation](#toolchain-installation).

# Participant Prerequisites

### Reading Materials

This section is reserved for preparation material that will be shared with the research group before the event.

- Reading pack link: _to be added_
- Background paper: _to be added_
- Workshop notes: _to be added_

## Registration

Use the link below to register:
- [Register](https://forms.office.com/r/2b0GsXpSwZ)


#### Toolchain installation

{{< emphasis-note >}}Participants should prepare their laptops before the event so the hands-on session can start on time.{{< /emphasis-note >}}

The setup script  _add GitHub link here_

```bash
# Step 1: download the Setup script
# for Linux / Mac ./install_toolchain.sh 
# for Windows ./install_toolchain.ps1

# Step 3: verify the toolchain setup
# for Linux / Mac ./verify_toolchain.sh
# for Windows ./verify_toolchain.ps1
```
