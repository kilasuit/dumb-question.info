---
id: 001
fuid: gh:kilasuit|dumb-question.info|ADR001
title: InitialADR
date: 2025-May-06
time: 06:30 UTC+1
# updatedDate: 2025-Apr-23
# updatedTime: 00:30 UTC+1 (UK BST)
attendees: 
- '@kilasuit'
#apologies:
outcome: Accepted
impactedAreas: 
- Repo Layout
- Repo Scope
- Tech Used
---
<!-- markdownlint-disable MD025 -->
# 001 - 2025-May-06 - InitialADR

## Status

Accepted 

See more in the Accepted , Declined & Deferred sections

## Context

This ADR highlights historic Decisions and is provided for context for this repo

## Decisions

### Decided by

@kilasuit - Ryan Yates

### Accepted

#### Documentation

This project will have useful AND up to date documentation to the best ability of the team

It will be in British English (i.e. not American English)

We would like at some point to build all of this and have it localised for accessibility and searchability, but that is not an initial goal for the project.

##### Use of ADR's

ADR's (Architecture Decision Records / Any Decision Records) are useful to allow users, including maintainers, to comeback to a project and understand why decisions were made. These can be linked to in Issues, and in comments in  code, allowing reviews at a later date.

ADR's can be either made public or kept private.

In this instance it was decided to make them public as part of the project & this initial ADR layout will be used in future projects as well.

##### Use of IINs, DINs & FINs Folders

This allows others to share theirs directly in this repo, if they choose to

#### Project Layout

The layout is as following most accepted practices, with a minor change in that all project docs are stored in a docs folder

This project author would like to have used a `.config` folder where all folders like `.vscode` `.github` & other configuration files could be contained but due to most tools expecting them in the root of the project, this not possible and is from a OCD perspective somewhat irritating. We hope future versions of software will allow for configurations to be contained in locations like this to keep things more organised.

As this is a simple 1 page site, the layout is as simple as possible 

#### Project Scope

To help people feel more up for asking those questions that they may feel they should prefix with either Dumb Question or Stupid Question & provide some context as to why they may not be.

#### Used Technologies

- VScode
  - VSCode is our editor of choice
  - We use the stable for most work but also make use of the Insiders build too
  - We will share settings in the .vscode folder with recommended extensions and settings, including spellings.

- GitHub
  - We use GitHub to host the public version of this repo
  - We use GitHub Issues, PR's and if ever needed Projects
  - We may have a need for using GitHub Actions in future (perhaps as an uptime checker)
  - We use GitHub Pages to host this site.
  
Commit flow
- Most changes are minor so maintainers can push to main
- External contributors can raise a PR
- PRs should use rebase merges


#### Project Marketing Plan

irRegular posts as needed & slides in decks when presenting.

May use a GH Action to comment on Bsky posts where the text in them either contains a variant of Dumb Question or Stupid Question 

### Declined

nothing to decline at this time

### Deferred

Should we include additional images or create a logos to use.

#### Long term plans - Post initial release

None at this time

### Notes

This repository and others, are part of the research I am doing on personal/business productivity in the world of software development and content creation based on any of the lessons learn in the research, development, deployment, review, continued development & re-deployment process. This is typically known as both ALM (Application Lifecycle Management) or SDLC (Software Development Lifecycle Management)

This will in time be publish and linked to my [public ORCiD profile](https://orcid.org/0009-0009-6030-3517) and will allow for [blog posts](https://blog.kilasuit.org) as well as a number of future presentations on this wider topic.
