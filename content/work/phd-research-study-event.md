+++
title = "PhD Research Study Event"
type = "work"
date = 2026-03-30
draft = false
+++

## Event Overview

The PhD research study event will be held on **10 May 2026**, with **gathering in front of the hotel at 12:30 PM** and the main program running from **1:00 PM to 6:00 PM** at the **Sheraton Hotel Novi Sad conference room**.

This session is designed for the research group to review study goals, align on workshop tasks, discuss the toolchain setup, and work through the planned study activities together.

> All registered participants will receive thank you gifts at the end of the event.

## Venue and Maps

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
| 1:45 PM - 2:45 PM | Lunch break organized at the hotel
| 3:00 PM - 3:45 PM | Toolchain preparation |
| 3:45 PM - 4:00 PM | Wrap-up discussion |
| 4:00 PM - 6:45 PM | Hands-on study session and wrap-up discussion |
| 6:45 PM - 7:00 PM | Thank you gifts and closing |

If you have dietary requirements, please include them in the registration form.

## Research Study Goals

The goal of the workshop is to compare how participants design communication architecture between AMPs using:

- a classical approach
- the HALO framework

During the hands-on work, participants should solve the same design problem in both approaches and record the same information for both, so the comparison stays consistent.

### Working Hypotheses

- **H1:** Using the HALO framework speeds up integration and development of AMP systems compared to the traditional approach.
- **H3:** Designing software architectures using the HALO framework gives better overview and maintainability compared to traditional methods.
- **H4:** The HALO framework provides portability and reuse of software architectural descriptions for different platforms with no or minimal effort.
- **H5:** The HALO framework gives better scalability and flexibility for IPC communication in AMP systems compared to already available solutions.
- **H6:** The HALO framework provides easier application partitioning and communication in heterogeneous SoC systems.

### What Participants Should Record

Participants should capture the same attributes for the **classical method** and for **HALO**:

- time needed to complete the task
- number of architecture elements or communication definitions created
- ease of defining communication attributes
- ease of updating or changing the architecture
- clarity of the overall architecture overview
- confidence in correctness of the solution
- perceived maintainability
- perceived scalability and flexibility
- perceived portability and reuse potential
- perceived ease of partitioning the application across AMPs
- comments, blockers, and questions during the task

### Study Task for Both Approaches

Participants will be asked to:

- design the communication architecture between AMPs
- define the same communication attributes in both approaches
- update the design when a change request is introduced
- compare how difficult it is to understand, modify, and maintain the solution

This makes the comparison between the classical approach and HALO more credible, because both tasks use the same scenario and the same set of recorded attributes.

## Laptop and Preparation

Please let us know one of the following when registering:

- you need a laptop provided on site
- you will bring your own laptop
- you are not yet sure and will confirm later

If you are bringing your own laptop, please also make sure you have administrator access so the required toolchain libraries can be installed during the workshop if needed.

# Participant Prerequisites

### Reading Materials

This section is reserved for preparation material that will be shared with the research group before the event.

- Reading pack link: _to be added_
- Background paper: _to be added_
- Workshop notes: _to be added_

## Registration

Use the link below to register:
- [Register](https://forms.office.com/r/2b0GsXpSwZ)


#### Toolchain installation Script

Participants should prepare their laptops before the event so the hands-on session can start on time.

TODO:
The setup script will be published on GitHub later.

- Setup script link: _add GitHub link here_

The script will prepare **WSL** and install the required development environment inside **Debian/Ubuntu on WSL**.

It will install:

- `build-essential`
- `cmake`
- `ninja-build`
- `git`
- `qemu-system-misc`
- `gcc-riscv64-unknown-elf`
- `binutils-riscv64-unknown-elf`
- `python3`
- `python3-pip`
- `python3-venv`
- `pipx`
- `device-tree-compiler`

It will also ensure:

- `west` is installed
- `pyelftools` is available in the `west` environment

#TODO:
Additional HALO Python libraries will be listed here later once the final package is ready.

### OneDrive Package

- Download link: _add OneDrive link here_
- Version / package name: _to be added_

### Installation Commands

Update this block once the package link and final toolchain dependencies are ready:

```bash
# Step 1: download the package from OneDrive
# TODO: add download instructions or local package path

# Step 2: install required libraries
# TODO: add platform-specific install commands

# Step 3: verify the toolchain setup
# TODO: add validation command
```
