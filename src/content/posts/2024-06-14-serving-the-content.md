---
title: Serving the content
description: Choose the host
date: 2024-06-14T14:00:22
image: /images/painting1.jpg
authors:
  - Dennis
tags:
  - dev
categories:
  - tech
---
I would have wanted to host the website on [GitHub Pages](https://pages.github.com/) that would be free for public repositories and would be a simple and straight forward solution. However, for the StaticCMS to be able to signin the authors to GitHub and to authorise them to push changes to the repo, another server is needed for OAuth. GitHub Pages would be a sufficient solution if authors would run the app locally, but when the StaticCMS is loaded on a real website, it will require a server for the OAuth App.

I chose to deploy the app on [Netlify](https://www.netlify.com/), because they have ready made solution for integrating StaticCMS with GitHub. In fact, StaticCMS is a descendant of their NetlifyCMS that no longer exists.

For the purpose and scale of this website, using Netlify is free.

I created the Netlify app from the GitHub repo, and now Netlify deploys a new version of the website whenever a commit is pushed to the repo.
