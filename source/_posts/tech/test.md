---
title: Test
categories:
- 其他
---
## Purpose
This is a test of evaluating [Hexo](https://hexo.io/) - a static site generating tool, mainly for blogging - to be used as the framework for new church web site.

A few reasons to try Hexo:
* Easy to use.
* Easy to customize.
* Clear separation between content and look & feel.
* Static site is easy to host. Advance features can be in serverless approach.
* Hexo has fairly big tech community - easy to find help.
* All the tools in the tool chain are free and open source.


## How it works
* Based on [Hexo](https://hexo.io/) framework.
* Theme of [snippet](https://github.com/shenliyang/hexo-theme-snippet) with some customization
* Main content in [Markdown](https://en.wikipedia.org/wiki/Markdown)

## How we can use it (without too much overhead).
* Separate team as 'content writer' and 'tech supporter'.
   * 'Content writer' provides content(post) in markdown format.
   * 'Tech supporter' creates and maintains website structure. We'll need graphic experts here as well.
* Content (output from 'content writer') could be hosted on either github or gitlab as a content repository.
* The generated website could be hosted as github/gitlab page.
* We'll utilize some online CI(e.g. Travis) tool to automate the process of generation and deployment. 
* Eventually the website will be auto updated whenever 'content writer' commits new content to github/gitlab. Only minimal 'tech support' need to be involved for updating.
   