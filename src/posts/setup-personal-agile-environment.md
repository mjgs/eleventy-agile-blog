---
title: Setup personal agile environment.
description: Setup a basic personal agile environment for managing tasks.
date: 2020-08-21 17:00:00.00 +7
tags:
  - Week34
layout: layouts/post.njk
---
The aim of the personal agile environment is to manage daily tasks in an agile way. The environment should be simple to setup and maintain.

Components:

1. Blog to describe work as it happens
2. Wiki to manage sprint details

The blog [homepage](/) has links to the 3 most recent blog posts, as well as links to the sprint wiki pages. It also has an archive of all posts.

It's the [eleventy](https://github.com/11ty/eleventy) [base blog](https://github.com/11ty/eleventy-base-blog) with a few minor customizations:

- Updated metadata.json
- Updated homepage yellow note
- Added links setion to the bottom of the homepage
- Create production branch for modifications

The wiki is an installation of [WikiJS](https://github.com/Requarks/wiki). Just the default install with a few pages:

- [Homepage](http://localhost:3000/en/home) that list of the sprints for the current year
- A page for each sprint

Agile Workflow:

1. Every week:

- Spring planning for upcomming week
- Spring implementation during the week
- Spring retrospective at end of week

2. Every 4 weeks:

- Spring planning for the next month
- Retrospective of the previous month

3. Every year:

- Spring planning for the next year
- Retrospective of the previous year

The exact way to use the wiki and blog varies by person, I tend to think of the blog as being the place where I narate the work, and the wiki as the place where I plan the work.
