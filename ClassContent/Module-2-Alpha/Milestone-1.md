# Milestone: Pivot

Walking the line between Waterfall and Agile can be difficult, but initially, getting off the ground requires a bit of planning and clear guidelines of how you intend to kick-off! That is the focus of this milestone. 

You likely have recently recently received a heavy round of feedback for your project. It is time to pivoting from your Initial Project Spec to your finalized Project Spec for this month. Pivoting can come in various degrees and is a term loosely used in our industry that means to modify our direction within a project.

How large of a pivoting, in this case, will be defined by you. Based upon the feedback you received from your MVP you will need to determine what changes you need to make to your initial idea as you bring that project to a full launch ready candidate.

## Milestone Pre-requisites

1. [x] Initial Pitch: Approved
2. [x] Initial Project Spec: Approved
3. [x] MVP: Approved

## Milestone Deliverables

1. [ ] Project Spec
2. [ ] Velocity Check

# Project Spec

The project spec should be a series of three markdown files contained within your repo in a folder on the root level labeled docs with a table of contents ```./docs/readme.md``` linking each major article (Brief, Spec, Project Milestones) to its proper section within each corresponding file. Each document should employ markdown formatting and good informational hierarchy techniques to convey their contents effectively.

A majority of this milestone's content will be a slight refactoring content you have already developed and with a light brush up based upon your lessons learned while developing your MVP in addition to some new sections researched this week.

## Project Spec Outline

* [Brief](#Brief)
    * [Audience](#Audience)
    * [Problem](#Problem)
    * [Solution](#Solution)
    * [Unique Value Proposition](#Unique-Value-Proposition)
    * [Pitch](#Pitch)
* [Spec](#Spec)
    * [Feature Definitions](#Feature-Definitions)
    * [Sitemap](#Sitemap)
    * [Interface](#Interface)
        * [Information Architecture](#Information-Architecture)
        * [Browser Support](#Browser-Support)
    * [Infrastructure](#Infrastructure)
        * [Technical Requirements](#Technical-Requirements)
        * [Programming Languages](#Programming-Languages)
        * [Integrations](#Integrations)
        * [Deployment Workflow](#Deployment-Workflow)
        * [Web Host](#Web-Host)

* [Project Milestones](#Project-Milestones)
    * [Initial Pitch](#Initial-Pitch)
    * [Initial Project Spec](#Initial-Project-Spec)
    * [MVP](#MVP)
    * [Pivot](#Pivot)
    * [Alpha Release](#Alpha-Release)
    * [Beta Release](#Beta-Release)
    * [Public Release](#Public-Release)

## Project Spec Details

### Brief

---

The Brief is an executive summary of all elements listed within. This should boil down to one long paragraph, devoting one to two sentences to each of the sections defined. Each section is then further defined in its own content.

### Audience

Define the primary audience and any secondary markets. The more specific the better. You should be defining the age, gender, education level, social background, level of familiarity with technology, and any other relevant and defining characteristics of the audiences you are intending to building your application.

Identify any members of these audiences you have had contact with, any interview notes or feedback summaries and a breakdown of considerations they have influenced.

### Problem

Clearly define the problem your audience is having. Cite any feedback from interviews with your audience. 

### Solution

Identify any competition operating in this market space and summarize how they are addressing the problem, as defined.

Define your solution and how it will directly address the problem your audience is having.

### Unique Value Proposition

What separates you from the competition? How are you able to better solve this defined problem for your audience than your competition? Why is your idea smarter, more efficient, or better?

### Pitch

Rehash your initial pitch content but incorporate all of your research and lessons learned with the MVP. This should be a short 1 - 3 min video. The audience for this should be expected to have no context of your previous pitch (like a potential employer), so make certain to include all the basic information:

* Identify Who You Are
* Identify Your **Primary Audience**
* **Research The Problem** They Are Having
* **Propose A Solution** To This Problem
* Identify Your **Unique Value Proposition**

Don't speak down to the your pitch's audience, but assume limited technical knowledge when explaining your concepts.

### Spec

---

No additional information is needed, this is simply a containing section to seperate the spec from the Brief's content.

### Feature Definitions

The Agile approach in the context of this course and how our workflow will work would be to create an issue for each feature on your Github repo. Each issue should titled and defined in detail as well as be labeled as a 'Feature'. In this section of the documentation you should link to the the issues with a filter applied to only show issues labeled as feature rather than duplicate your efforts by copy/pasting that content into a second place. 

> Note: you may need to [create a label](https://help.github.com/articles/creating-a-label/) called feature

### Sitemap

Create and label a hierarchical diagram that identifies all user facing screens. This will be the road map your instructors and you will use to converse about various screens and to examine user flows between screens.

### Interface

Similar to the Spec section, this is a container section that separates section contents from other sections.

### Information Architecture

Using your sitemap as a base structure, use this section to house ALL of your text content. This is a great place to develop all of the content that will appear on your pages, components, and sub sections outside of the constraints of code. In MVC we seperate views from controllers and models, while in the Information Architecture section of your project spec you will separate your content from your code.

### Browser Support

Which browsers, operating systems, devices, portrait and landscape do you plan to support? How did you come to this decision and what are the technical specification resolutions of these devices?

### Infrastructure

Visually diagram the Server portion of the Client Server Request Model. Label each part and summarize the physical or virtualized server totals.

### Technical Requirements

Define the server software and hardware, virtualized or not, that your application requires to run. These should be in a format of Title: Brief description of my usage. If a feature as defined in the issues requires a specific technology, that issue should cite this as well. 

> Example: Technical Requirement - FFMPEG
> Server side service to handle video. Needed to extract single frames to turn into thumbnails.

> Example: Issue - Thumbnail Generate:
> Detailed description of the usage I intend to do... how exactly that will work for the user.
> Technical Requirement: FFMPEG

### Programming Languages

Identify what programming languages you are using. Provide links to their respective documentation sites.

### Integrations

Identify what 3rd party packages, libraries, or external integrations you are using. Provide links to their respective documentation sites.

### Deployment Workflow

Document the release process for your application from new feature creation through live deployment. This will be heavily focused on this week's research.

### Web Host

Define what hosting service provider you will be utilizing and identify the accessible urls of any live or staging servers for review.

### Project Milestones

---

Similar to the Spec section, this is a container section that separates section contents from other sections.

### Initial Pitch

Link to your initial Pitch Video.

### Initial Project Spec

Link to your initial Project Spec.

### MVP

Direct Link to the tagged release of your MVP on your repo.

> This should be a link to a specific commit.

### Pivot

Direct Link to the tagged release of your Pivot on your repo.

> This should be a link to a specific commit.

### Alpha Release

Date of the Alpha Release Milestone

### Beta Release

Date of the Beta Release Milestone

### Public Release

Date of the Public Release Milestone

# Velocity Check

At the end of the week your progress will be evaluated to see how many story points you have earned. Successfully completed issues will be tallied and a velocity will be established to help provide a baseline for the following week's work for you. You are able to use this velocity check to estimate if you are on track for completion of your final milestones from early steps. This relies on accurate and honest usage of the issue system.

The Velocity Check will be calculated and posted for your review. Your role in this requirement is to maintain your progress within the issue system of github and accurately estimate story points per issue.

This is a pass/fail assignment where failing represents a significant drop in velocity, attributed to not using the issue system to correctly communicate, with the Capstone Team, your accurate progress or neglecting to make progress toward your set goals.


---

Lecture Material:

Github Issue Client note action items
Diagraming Servers
Deployment Workflow
Velocity Check