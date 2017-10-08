<img src="https://user-images.githubusercontent.com/3791941/31036931-072760fe-a534-11e7-8cd7-0565bdc2727c.png" width="100" height="60">

# How High Performing Teams use Heroku Flow

- Tentative Time: 3:00-4:30
- Length: 90 minutes
- Format: Hands-on, building, interactive

## Facilitator

### @joshwlewis

<img src="/images/joshwlewis.png" alt="Josh W Lewis" width="100">

Josh W Lewis is a multi-discipline engineer who has been building
web applications and development tooling for nearly a decade. Lately, he's
been building new workflows for developers on GitHub, delivering
Heroku Pipelines and Review Apps and leading the development of Heroku CI as
part of a small, high-performance team.

## Abstract

Continuous Integration and continuous delivery are the key to code quality, product agility, and engineering velocity. In this session, you’ll learn how your team can use GitHub, Heroku Pipelines, and Heroku CI to make continuous delivery simple and flexible. The Git-based methodology provides for a pipeline through which code begins as a fully executable pull request, goes through automated unit and integration tests, is automatically merged to test and staging apps, and is then deployed to production with a single click. Some customers are able to deploy features and fixes up to 500+ times a week, with very few rollbacks from production. Developers with an intermediate level of experience will benefit the most from this workshop.

## Prerequisites

Requirement | Mandatory? | Where to get it | Comments
--- | --- | --- | ---
An internet connection | Yes | Conference WiFi |
A modern web browser | Yes | [google.com/chrome](https://www.google.com/chrome) |
A Heroku account | Yes | [signup.heroku.com](https://signup.heroku.com) | 
A verified Heroku Account | No | [dashboard.heroku.com/account/billing](https://dashboard.heroku.com/account/billing) | A credit card is required for advanced features like addons and CI.

## Resources

- [Slides](https://docs.google.com/presentation/d/11kTyYGi9GdAUgRxz_R0ln8IDijYrX1lU454puigdEIE/edit?usp=sharing)
- Demo Repository: [heroku/memefab](https://github.com/heroku/memefab)

## Outline

### 0:00 - Introduction

- Hi, I'm Josh
- What is Heroku?
  - Brief description; TL;DR it's a PaaS
  - Quick walkthrough of demo app
- What are Heroku Pipelines?
  - A workflow designed for high-performing teams
  - Builds on workflows you already have in GitHub
  - Illustrate the full development workflow GIF

### 0:10 - Demo/Hook

- Showcase the entire workflow
  - Open a PR
  - Inspect the PR app
  - Check CI test results
  - Merge the PR
  - Watch staging auto-deploy
  - Inspect staging
  - Check CI results
  - Promote to prod

- Your turn! We'll guide you through
  - Setting up a Pipeline
  - Setting up automatic deploys to staging
  - Setting up automatic review apps
  - Setting up automatic CI runs
  - Setting up promotions to production
  - Taking a feature from development through staging and to production

### 0:25 - Prerequisites

- A web browser (tablet or laptop is fine, smartphone is harder, but should work)
- An internet connection
- A GitHub account (logged in)
- A Heroku account
- Pause for 5 minutes, staff helps folks get on wifi, create/login to accounts

### 0:30 - Iteration 1

- Walkthrough
  - Fork the sample repository
  - Create a staging app (via Heroku Button)
  - Add it to the pipeline
- Pause for Q&A, staff patrolling and helping perform steps

### 0:40 - Iteration 2

- Walkthrough
  - Connect pipeline to your repository
  - Enable automatic deploys
  - Enable review apps
- Pause for Q&A, staff patrolling and helping perform steps

### 0:50 - Iteration 3

- Walkthrough
  - Create production app (via Heroku Button)
  - Add it to the same pipeline
- Pause for Q&A, staff patrolling and helping perform steps

### 0:60 - Iteration 4

- Walkthrough
  - Enable CI
    - caveat: this step is optional because it costs a few cents and requires CC
- Short pause for Q&A, staff patrolling and helping perform steps

### 0:65 - Iteration 5

- Walkthrough
  - Ship a feature
    - Open a PR
    - Inspect the PR app
    - Check CI results for feature branch (if applicable)
    - Merge the PR
    - Watch auto-deploy to master
    - inspect staging app
    - Check CI results for master (if applicable)
    - Promote to prod
    - Inspect running prod app
- Short pause while attendees work through steps

### 0:75 - Q&A
