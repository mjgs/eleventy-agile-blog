# eleventy-agile-blog

A minimal blog template using [Eleventy](https://github.com/11ty/eleventy), this one implements a simple agile development workflow so you can get stuff done.

## Description

Of course there are lots of great tools for managing agile development and if you are working in teams you should most likely use those. 

But this project is a great way to manage your own development.

- Everything is managed in files
- Never worry about your workflow breaking because of software incompatibility
- Build your muscle memory of the agile development process

You can run it locally or deploy on something like netlify if you want to have everything public.

Use it for managing writting code or just for managing any set of tasks you need to complete.

I don't claim to be in any way an expert in the agile way. There are probably places where it's not "the agile" way. I'm open to pull requests.

Stop procrastinating, write a blog post, re-focus on what you need to get done, then do it.

## Based on

I have based this repo on the [eleventy-base-blog](https://github.com/11ty/eleventy-base-blog), the biggest obvious difference is files are in src and dist folders. I find that makes it easier to jump around the project quickly.

## Demos

* [eleventy-agile-blog.markjgsmith.com](https://eleventy-agile-blog.markjgsmith.com)

## Getting Started

```
git clone https://github.com/11ty/eleventy-agile-blog.git my-blog-name
cd my-blog-name # Update `.eleventy.js` with your details
npm install
npm start
```

## How the agile development workflow works

Use blog posts to describe your work, what you did, what you are about to do, then create "stories" that you add to the "backlog". Assign stories to "sprints", these last 1 week. Flesh out the stories, implement them, and then move these to "done" when you complete them. 

At the end of the week do a retrospective of what you did, and plan (i.e. create and assign stories to the next sprint) for the upcomming week.

Whenever you are a bit unsure of your path, read the above 2 paragraphs. You probably need to write a blog post.

The blog has the following pages:

- Home - Shows the past 3 blog posts and some useful links
- Archive - Shows all your blog posts
- Sprints - Shows all your sprints
- Backlog - Shows all your uncompleted stories
- Done - Shows all your completed stories
- About Me - A place to add contact details and personal info

Read the workflow description from the [week34 retrospective](https://festive-haibt-b7ead0.netlify.app/stories/retrospective-week34/) to get a better idea of how I am using the blog.

## Notes

- Sprints in /sprints must use the same file name pattern
- Add tag 'backlog' to a story to add it to the backlog page
- Add tag 'done' to a story to add it to the done page
- Regulary check in your changes to git
  - Create a week branch (e.g. week34)
  - Create story branches from your week branch
  - Merge story branches into the week branch
  - Merge week branches back into master
- Read up on [how eleventy works](https://www.11ty.dev/docs) so you can customise the blog
- You might want to add some git aliases to your shell to streamline working with git commands

Hopefully my description makes some sense, let me know how I could improve these docs.
