# Pyronear roadmap 2026-2027

This repository holds the **epics** of the Pyronear roadmap. Each epic is an issue; its sub-issues live in the repository where the work happens (`pyro-engine`, `pyro-api`, `new-pyro-platform`, `vision-rd`, `pi-manager-template`, ...). The whole roadmap is followed in the GitHub project **Roadmap 26-27**.

## The five axes

| Axis | What it is about |
|---|---|
| **A · Community** | **Grow and empower the community.** Stations built by volunteers, annotation, datasets, a larger network of connected cameras. |
| **B · Detection quality** | **Better detection: fewer false alarms, more precise detections.** Temporal model, fire localisation, occlusion masks, camera support. A more precise detection also enriches the alert (a precise location, a reliable score). |
| **C · Alert tools** | **Enrich the tools that support alert analysis and follow-up.** Be even more useful when an alert fires, and on days with many fires: platform, livestream, triangulation, sharing. |
| **D · Foundations** | **Make our services more reliable and professional.** Authentication, deployments, monitoring, website, documentation. |
| **E · Scale** | **Streamline processes and save time.** The technical and organisational setup that lets us scale: automated setup and calibration, visibility analysis. |

## Periods and priorities

| Period | When |
|---|---|
| 🎄 **T4-26** | October to December 2026 |
| 🌱 **T1-27** | January to March 2027 |
| 🌸 **T2-AprMay-27** | April and May 2027: must be in production by the end of May |
| ☀️ **T2-Jun-27** | June 2027: finishing; the fire season may start during June |
| **Later** | After the fire season |

| Priority | Meaning |
|---|---|
| **P1** | Impossible to do without before next summer |
| **P2** | It would be a pity not to have it |
| **P3** | We can do without it if needed |

## How to read the project

The project has one view per use:

- **Roadmap Overview** and **Story**: the epics, by period and by axis. Start here to see the year.
- **Team week**: what the team works on this week.
- **To pick up (weekly)**: tickets nobody has taken yet, by axis and priority.
- **Contributors**: tickets open to volunteers (`good first issue`), with no assignee.
- **Blocked / at risk** and **No axis or period**: what needs attention.

Each item has an **Axis**, a **Priority**, a **Period** and a **Status** (To pick up, In progress, In review, Done, Blocked). Team members also use the **Week** field.

## How the work is organised

- An **epic** is a large goal. It lives here, in `pyronear/roadmap`, and has the label `epic`.
- A **sub-issue** is a task. It lives in the repository where the code is, and is attached to its epic. Its first line says which epic it belongs to.
- A topic that touches only one repository can be a plain issue in that repository, or a sub-issue of an epic here.
- Some epics are marked **[DRAFT]**: the idea is written down, but not scoped yet.

## Contribute

- Open the **Contributors** view of the project, or look for the label `good first issue` in any repository.
- Pick a ticket without an assignee, say so in a comment, and open a pull request.
- Open a question in `roadmap` if you have an idea that does not fit an existing epic.
- Each repository has its own `CONTRIBUTING.md`.

## Current epics

The list of epics is the list of issues labelled `epic` in this repository.
