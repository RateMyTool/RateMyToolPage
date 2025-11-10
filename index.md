# RateMyTool(s)

![ci-badge](https://github.com/YOUR-ORG-NAME/YOUR-REPO-NAME/workflows/ci-YOUR-REPO-NAME/badge.svg)

## Table of Contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Team](#team)

## Overview

### The Problem

UH Manoa students are constantly searching for effective online learning resources to supplement their coursework—from video tutorials and practice platforms to AI tools and study aids. However, there is no centralized, student-driven platform where they can discover which tools actually work.

### The Solution

RateMyTool(s) is a community-driven review platform specifically for UH Manoa students to rate and review online learning resources, AI tools, and educational platforms. Similar to RateMyProfessor but for digital learning tools, students can:

* Search for resources by course code (e.g., ICS 314)
* Browse by category (e.g., coding practice, math tutoring, AI assistants)
* Search by tool name (e.g., Khan Academy, ChatGPT, Codecademy)
* View aggregate ratings and detailed student reviews
* Filter tools by specific UH Manoa courses
* Upvote helpful reviews and save favorite tools
* Receive personalized recommendations based on major and courses

## Deployment

*(Coming soon - link to deployed application)*

## User Guide

This section provides a walkthrough of the RateMyTool(s) user interface and its capabilities.

### Landing Page

The landing page is presented to users when they visit the top-level URL of the site.

*(Mockup image coming soon)*

The landing page features:
* Overview of the platform's purpose
* Featured tools and recently reviewed resources
* Trending tools among UH Manoa students
* Prominent search bar for quick discovery

### Tool Directory / Browse Page

*(Mockup image coming soon)*

A searchable and filterable catalog organized by:
* Categories (AI Tools, Video Platforms, Practice Sites, Study Aids)
* UH Manoa departments and course prefixes
* Rating levels and popularity

### Individual Tool Profile Page

*(Mockup image coming soon)*

Each tool has a dedicated profile page displaying:
* Overall rating (5-star system)
* Student reviews with course tags
* Related/similar tools
* External link to the actual tool
* Course-specific feedback

### Add Review Page

*(Mockup image coming soon)*

Form for students to:
* Rate a tool across multiple dimensions
* Tag relevant UH courses
* Write detailed feedback
* Specify major and year for context

### Course-Specific Landing Pages

Dynamic pages (e.g., `/course/ICS314`) showing highly-rated tools reviewed specifically for that course.

*(Mockup image coming soon)*

### User Dashboard

Personalized dashboard featuring:
* Reviews you've written
* Saved/bookmarked tools
* Personalized recommendations based on your major and courses
* Contribution statistics

*(Mockup image coming soon)*

## Community Feedback

*(This section will be updated with feedback from UH community members after deployment)*

## Developer Guide

This section provides information for developers wishing to use this code base as a basis for their own development tasks.

### Installation

First, [install PostgreSQL](https://www.postgresql.org/download/). Then create a database for your application.

Second, go to [https://github.com/YOUR-ORG-NAME/YOUR-REPO-NAME](https://github.com/YOUR-ORG-NAME/YOUR-REPO-NAME), and click the "Use this template" button. Complete the dialog box to create a new repository that you own that is initialized with this template's files.

Third, go to your newly created repository, and click the "Clone or download" button to download your new GitHub repo to your local file system. Using [GitHub Desktop](https://desktop.github.com/) is a great choice if you use MacOS or Windows.

Fourth, cd into the directory of your local copy of the repo, and install third party libraries with:
```
$ npm install
```

Fifth, create a `.env` file from the `sample.env` file. Edit the `.env` file to set the `DATABASE_URL` to point to your PostgreSQL database.

### Running the system

Once the libraries are installed and the database is configured, you can run the application by invoking:
```
$ npm run dev
```

The first time you run the app, it will create default data in the database.

### Viewing the running app

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### ESLint

You can verify that the code obeys our coding standards by running ESLint over the code in the src/ directory with:
```
$ npm run lint
```

## Development History

The development process for RateMyTool(s) conformed to [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/) practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

The following sections document the development history of RateMyTool(s).

### Milestone 1: Mockup Development

The goal of Milestone 1 is to create HTML mockups of the pages in the system.

Milestone 1 is managed using [RateMyTools GitHub Project Board M1](LINK-TO-PROJECT-BOARD):

*(Screenshot of project board coming soon)*

### Milestone 2: Data Model Development

*(Coming soon)*

### Milestone 3: Final Touches

*(Coming soon)*

## Team

RateMyTool(s) is designed, implemented, and maintained by:

* [Joseph Creollo](https://github.com/YOUR-GITHUB-USERNAME)
* [Henry Korver](https://github.com/YOUR-GITHUB-USERNAME)
* [Justin Iwata](https://github.com/justiniwata)
* [Kade Komeya](https://github.com/YOUR-GITHUB-USERNAME)

Team Portfolio Pages:
* [Joseph Creollo Portfolio](PORTFOLIO-LINK)
* [Henry Korver Portfolio](PORTFOLIO-LINK)
* [Justin Iwata Portfolio](https://justiniwata.github.io/)
* [Kade Komeya Portfolio](PORTFOLIO-LINK)
  
