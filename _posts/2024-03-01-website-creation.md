---
title:  "How I Made This Website with Github"
date: 2024-03-01
excerpt: "March 1, 2024"
layout: single
header:
  teaser: "../assets/images/website-creation-post/teaser.jpeg"
---

I think an appropriate first post is to describe how I built this website, hopefully making it easier for you than it was for me. My goal is for the website to be a landing page with links to my various professional pages, include information about my research, and host blog posts like this one. For the design, I wanted something minimalistic and streamlined so that I did not have to make a lot of adjustments over time. 

I was drawn to using GitHub Pages as my website builder because my work is computational, and GitHub is the most trusted platform to host code. Although this route is not as user-friendly as others (e.g. Squarespace, Wix, etc.), it is free, and my website URL matches my GitHub page. As a bonus, it inherently requires extra practice using GitHub and Git commands, which I am always trying to get better at.

If you’re ok with a little pain and a lot of gain, follow along to make your own GitHub website! 

## Setup

Free, pre-designed [templates from Jekyll](https://jekyllthemes.io/free) can be directly incorporated into a GitHub Pages website. I chose the [Minimal Mistakes](https://jekyllthemes.io/theme/minimal-mistakes) theme, then clicked the button `Get Minimal Mistakes on GitHub` at the top of the landing page.

<figure>
  <img src="../assets/images/website-creation-post/pic1.jpg" alt="Get Minimal Mistakes on GitHub">
</figure>

I tried a few options described [here](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/), but the easiest method was to fork the [repository](https://github.com/mmistakes/minimal-mistakes) from GitHub. 

<figure>
  <img src="../assets/images/website-creation-post/pic2.jpg" alt="Fork Minimal Mistakes Repository">
</figure>

For your site, you should name the forked repository `[github-username].github.io`. I tested naming it something other than my GitHub username and ran into problems building the website. Next, I went to my GitHub page, navigated to the new repository called `[github-username].github.io` and clicked `Settings`. I set the "Default branch" to "master". Then I clicked “Pages” on the sidebar under “Code and automation”. I chose `Deploy from a branch` from the drop-down under “Source” and set it to “master”. Then I was able to deploy the site by clicking `Visit site`. 

<figure>
  <img src="../assets/images/website-creation-post/pic3.jpg" alt="Deploy GitHub website">
</figure>

For now, your site is an exact replica of the Jekyll template. Following Jekyll’s recommendation, I cleaned up the repository by removing the following folders and files that aren’t needed for my personal website:
- `.editorconfig`
- `.gitattributes`
- `.github`
- `/docs`
- `/test`
- `CHANGELOG.md`
- `minimal-mistakes-jekyll.gemspec`
- `README.md`
- `screenshot-layouts.png`
- `screenshot.png`

## Customization