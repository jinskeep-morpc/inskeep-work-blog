---
title: Website Setup
date: 2025-08-18
tags:
    - setup
    - website
    - blog
---

# Setting up this website.  

When starting this website, I needed to decide on a static site generator to serve the site to github pages. 

<!--more-->

## Choosing a Static Site Generator.  

- [jekyll](https://jekyllrb.com/)
    - Appears to be phasing out in popularity for better, lightweight options.
- [hugo](https://gohugo.io/getting-started/quick-start/)  
    - Hearing great things about it, but the documentation is rough to follow. 
    - I have had better luck following documentation for themes when getting started (see next header)
- [mkdocs](https://www.mkdocs.org/getting-started/)
    - Lightweight and simple. Really would prefer something like this. 
- [MyST](https://mystmd.org/guide/)
    - Jupyter support. Use it for work documentation. My switch to this at some point. But themes were limited. 

Ultimately I landed on Hugo due to a want to learn it and also the theme options are great. 

## Hugo Hextra Theme

[https://imfing.github.io/hextra/](https://imfing.github.io/hextra/)

The hextra theme seemed like a decent decision. It has:

- A clean look
- Good documentation.
- Easy blogging ability
- Search
- Expandability
- Full markdown support including [GitHub Flavored MD](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## Blog setup

Getting started on the blog was as simple as writing this markdown file and pushing the changes to github.

### Some notes:

When writing new blog posts, the card is automatically populated. In the yaml at the beginning of the post add `title:` and `date:`. When writing the post add `<!--more-->` to where you want the text preview for the card to stop.

> [!CAUTION]
> Watch out for whitespace in the yaml at the head of the document. This gave me some confusion why tags were not working. 

