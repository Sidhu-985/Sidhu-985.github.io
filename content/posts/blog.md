+++ 
draft = false
date = 2024-02-03T14:48:00+05:30
title = "Process of making this website"
description = "Using Hugo"
slug = ""
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++

A brief explanation of my journey in making this website
<!--more-->
## Figuring out what Hugo actually is
When I first saw that the task-2 is about buliding a website,I was quite intimidated as I have no idea to write the html,css or js code.But that's when I noticed about [Hugo](https://gohugo.io/).
Hugo is a static website generator and I used the terminal to do so.I learnt  new hugo commands along with some git commands.I also read the [quickstart guide](https://gohugo.io/getting-started/quick-start/) which provided the steps inorder to build this website.

You can choose any theme from [Hugo-themes](https://themes.gohugo.io/) to build the website.

## Unexpected Errors
Everything was fine untilit wasn't.When I finally created the site I tried to push it into my repository.But after pushing the gitpages were checking the files by delploying so that it can create an actual link to the public.
But there was some error during the check process.So I googled about it and checked the settings and changed it according to the media.

Later after alot of reasearch I still couldn't find the solution to solve this.So I asked one of my friends to check on it, and *BANG* they solved.
So shoutout to them.

**Note:Read the whole docs before trying hugo.**
## Commands that I used
* `hugo new site <site name>`:-This basically creates a new site within the current directory(Repository).
* `git submodule`:-Lets us use external repositories into our own repo.
* `hugo server`:-Builds the site with the changes that we made in configurations.
* `hugo`:-Publishes the site.
* `hugo new posts/<post name.md>`:-To create a new post in content directory.
* `nano`:-Open the text file and we edit it.

## Things I learned
* How to use hugo to create static webpages 
* How to import themes into hugo and customize them
* The `git submodule` command, which lets us use external repositories in our own repo's.
