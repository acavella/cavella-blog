---
title: New design, new CMS
slug: new-design-new-cms
authors: cavella
tags: [tutorials]
---

This blog has been a constant evolution changes and improvements. It started as a very simple Jekyll based blog utilizing the Simple.css framework. Seeking further customization and a more of a modern design I set out to build my own theme based on Bootstrap. While both of these iterations were great, I kept coming back to what I felt are short comings of Jekyll itself as a CMS.

## Advantages

Let start by saying that I really like Jekyll and it does everything that is should and does them well.  By leveraging Github and a host like Netlify, Jekyll allows you to deploy a website or blog that is super lightweight and deploys in an instant. The "templating" system is very flexible and makes it possible for a relative amateur such as myself to build a pretty nice looking blog. 

Writing posts was at a high level easy enough, simple markdown format. Using VSCode or any other simple editor made this a simple enough process. However, this about where my love affair with Jekyll and its workflow ended.

## Challenges

As I alluded to in the previous section, the editing workflow was one of my biggest challenges with Jekyll.  Although markdown is simple enough and allowed me to push out a nicely formatted post with very little effort, there were some challenges.

The publishing workflow itself was rather challenging and moving posts from a draft status to a published status was a slightly clunky workflow. This required me physically moving files from one folder to another and editing the frontmatter of the post to indicate it was published. 

Embedding images further complicated matters. Markdown lacks the additional formatting options that one might want when manipulating images within a post. This is further complicated by the fact that you are not dealing with a WYSIWYG editor. I often found I would publish a new article and then once rendered I'd have to adjust the images and other non-standard items multiple times before getting it right. 

## Solution

I have a long history with other CMS platforms prior to Jekyll, mostly Wordpress. I have run multiple blogs and websites using Wordpress and became very comfortable with a lot of its features. However, Wordpress has developed from a simple blog platform to a do everything toolbox. Even at its core, Wordpress of today seems pretty heavy weight to generate a simple personal blog that might serve a few new posts per year. 

Over the years I've looked at Ghost a few times and even deployed it maybe once or twice.  However, I've always found its use of Node.js a little confusing and just something I didn't really want to learn. It just so happens I came across an article [Self-Hosted Blogging Made Easy with Ghost on Noted.lol](https://noted.lol/ghost-cms/). This article contained a very simple Docker based deployment for Ghost. In the spirit of one my main topics, homelabs and self-hosting, I decided to deploy my new Ghost blog on one of the Raspberry Pis in my homelab. 

Ghost has checked all of the boxes for me. It is a very lightweight deployment, which renders pages in an instant. On top of that there is just less for me to worry about managing. There are plenty of freely available themes that take the guesswork out building a site and no matter how proud I was of my DIY Bootstrap theme, it had its shortcomings, I'm no developer. 

The biggest problem Ghost solves for me is the addition of a WYSIWYG editor in the workflow. Editing and publishing posts within Ghost is a breeze allowing me to use any combination of markdown, images, etc... Everything is modify and viewed in real-time.  

Hopefully this is my last blog / CMS change for a while.  Overall, I'm quite happy with everything it has to offer and I can focus more of my time on the content.
