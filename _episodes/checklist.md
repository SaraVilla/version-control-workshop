---
title: "Workflow checklist" # title of the episode
teaching: 5 # time required to teach (minutes)
exercises: 20 # time required for participants to do the activities (minutes)
duration: 0 # duration not included in teaching/exercises time (minutes)
# summary of the episode content for displaying on the schedule page
summary: >-
  A checklist to help you ensure your workflow includes the topics covered today.
questions:
  - What will I do?
  - When will I do it?
  - How will I remember to?
objectives:
  - Be confident you'll remember to implement the skills learned here today.
keypoints:
is-break: false
ukrn_wb_rules: # list of rules for the UKRN Workshop Builder tool
day: 1
order: 200000
---

## How to use this checklist

* Copy the checklist to a new document.
* For each item, think about what it involves, and when you will do it.
* Consider how you might remind yourself to do it, or persuade yourself to make time for it.
* As you come up with your answers, write them in the space provided, or tick one of the existing suggestions.
  * The suggestions are roughly in the order of recommended best practice.
* When you've answered all the points in a section, tick it off.

## Checklist

### Licensing [ ]

- I will find out who will be the rights holder for the software
  - [ ] _When I apply for funding_
  - [ ] _At the beginning of the project_
  - [ ] _When I put the code on [a repository](#repository--)_
  - [ ] _When I make [the repository](#repository--) public_
  - [ ] _When ______________ gets back to me, and I'll chase them if they haven't by _______________._
  - [ ] _______________________________________________________________________________.

- I will decide on what license to apply to the software
  - [ ] _When I've found out who the rights holder is_
  - [ ] _When I make [the repository](#repository--) public_
  - _______________________________________________________________________________.

- I will review the license applied to the software
  - [ ] _When I add [new dependencies](#dependencies--)_
  - [ ] _______________________________________________________________________________.

### Documentation [ ]

- I will write instructions for using the code
  - [ ] _When I start to [write code](#code--)_
  - [ ] _When I put my code on [a repository](#repository--)_
  - [ ] _______________________________________________________________________________.
- I will document the code using
  - [ ] _Recognised standard tools (e.g. [Doxygen](https://www.doxygen.nl/index.html))_
  - [ ] _Separate documents_
  - [ ] _Inline comments_
  - [ ] _______________________________________________________________________________.
- I will update the documentation
  - [ ] _As I make changes to [the code](#code--)_
  - [ ] _At a set time each day/week/month/__________
  - [ ] _Before I [publish a new version](#publishing--)_
  - [ ] _______________________________________________________________________________.
- I will publish the documentation
  - [ ] _Automatically using continuous integration_
  - [ ] _Whenever I [publish a new version of the software](#publishing--)_
  - [ ] _______________________________________________________________________________.

### Code [ ]

- I will make the code readable
  - [ ] _As I write it_
  - [ ] _Once things are working like they should_
  - [ ] _Before I [publish a new version](#publishing--)_
  - [ ] _______________________________________________________________________________.

- I will organise my files
  - [ ] _Using a well-planned and clear directory structure_
  - [ ] _______________________________________________________________________________.

### Dependencies [ ]

- I will make sure my dependencies are listed
  - [ ] _Using a full environment management system (e.g. Docker, Apptainer)_
  - [ ] _Using automated dependency management tools (e.g. conda, renv)_
  - [ ] _By automatically documenting them when the code runs_
  - [ ] _By including them in [the documentation](#documentation--)_
  - [ ] _______________________________________________________________________________.
- I will review my dependency list
  - [ ] _Automatically using dependency management tools_
  - [ ] _When I add or remove a dependency_
  - [ ] _Before I [publish a new version](#publishing--)_
  - [ ] _______________________________________________________________________________.

### Tests [ ]

- I will test my software
  - [ ] _Using a testing framework (e.g. Cypress, pytest, testthat)_
  - [ ] _By having a set of things I do every time_
  - [ ] _______________________________________________________________________________.

- I will run my software tests
  - [ ] _Automatically using continuous integration_
  - [ ] _Before I push to [the repository](#repository--)_
  - [ ] _Before I [publish a new version](#publishing--)_
  - [ ] _______________________________________________________________________________.

### Repository [ ]

- I will upload my code to
  - [ ] _A dedicated code repository (e.g. GitHub)_
  - [ ] _A well-resourced repository (e.g. OSF, FigShare, Zenodo, university repositories)_
  - [ ] _A personal website_
  - [ ] _______________________________________________________________________________.
- I will make the code publicly accessible
  - [ ] _By enabling the approriate permissions in the repository_
  - [ ] _By [publishing](#publishing--) specific versions_
  - [ ] _______________________________________________________________________________.

### Publishing [ ]

- I will publish my code by
  - [ ] _Issuing releases on a [code repository](#repository--)_
  - [ ] _Ensuring the [code repository](#repository--) is publicly accessible_
  - [ ] _______________________________________________________________________________.
- I will do this
  - [ ] _Whenever [milestones](#collaboration--) are reached_
  - [ ] _Whenever I publish a related output (e.g. research paper)_
  - [ ] _Automatically whenever I push to [the repository](#repository--)_
  - [ ] _______________________________________________________________________________.

### Referencing [ ]

- I will make my code citable by
  - [ ] _Publishing [specific releases](#publishing--) with a DOI (e.g. via Zenodo)_
  - [ ] _Writing a technical/methods paper and submitting it to a journal_
  - [ ] _Citing [specific releases](#publishing--) directly_
  - [ ] _Citing [the repository](#repository--) with a time/version stamp_
  - [ ] _Citing [the repository](#repository--) only_
  - [ ] _______________________________________________________________________________.
- I will do this
  - [ ] _When I [publish](#publishing--) the code_
  - [ ] _When I publish a related output_
  - [ ] _______________________________________________________________________________.

### Collaboration [ ]

- I will make it
  [easy for others collaborate](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007296#sec007)
  on my code by (tick all that apply)
  - [ ] _Using collaboration-friendly services like GitHub_
  - [ ] _Writing a welcome guide for new contributors_
  - [ ] _Having easy templates for users to submit bug reports and feature requests_
  - [ ] _Ensuring a welcoming attitude for contributors_
  - [ ] _______________________________________________________________________________.
  - [ ] _______________________________________________________________________________.
  - [ ] _______________________________________________________________________________.
  - [ ] _______________________________________________________________________________.
