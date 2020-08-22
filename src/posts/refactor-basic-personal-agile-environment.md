---
title: Refactor personal agile environment.
description: Refactor basic personal agile environment for managing tasks.
date: 2020-08-22
tags:
  - agile
  - week34
layout: layouts/post.njk
---
I made some good progress yesterday in [setting up my personal agile environment](/posts/setup-personal-agile-env).

Today I am refactoring the setup slightly by moving the wikijs setup into the notes blog. This will simplify setup considerably.

After reviewing the setup it was clear that the only two features I was using from wikijs that are not present in the notes blog are:

- Markdown editor
- Search

I can use [VSCode](https://code.visualstudio.com) for markdown editing, and for search I can grep files on the file system. It makes sense to use the blog for managing sprints.

Using VScode is in many ways better because it has lots of text editing tools so for instance search and replace is a lot quicker.

WikiJS might be used for more involved projects later down the line.

I will at a later date figure out a better search feature.

Todo:

- ~~Create sprints page in notes blog~~
- ~~Add sprints to notes blog navigation~~
- ~~Re-arrange dir structure so files are in src and dist folders~~
- ~~Create sprints page from sprint files in /sprints~~
- ~~Install nunjucks vscode syntax highlighting plugin~~
- ~~Create backlog page in notes blog~~
- ~~Add backlog to notes blog navigation~~
