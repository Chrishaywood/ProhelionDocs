---
title: "Index"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: Prohelion builds high powered, ultra light weight, mobile energy solutions, to power the vehicles and minds of the future.
---

{% include note.html content="If you have any comments or feedback please don't hesitate to contact us" %}

## Big Title 1

Follow these instructions to build the theme.

### 1. Sub Title 1

First, download or clone the theme from the [Github repo](https://github.com/tomjoht/documentation-theme-jekyll). Most likely you won't be pulling in updates once you start customizing the theme, so downloading the theme (instead of cloning it) probably makes the most sense. In Github, click the **Clone or download** button, and then click **Download ZIP**.

### 2. Sub Title 2

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

* [Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
* [Install Jekyll on Windows][mydoc_install_jekyll_on_windows]

### 3. Sub Title 3

In case you haven't installed Bundler, install it:

```
gem install bundler
```

You'll want [Bundler](http://bundler.io/) to make sure all the Ruby gems needed work well with your project. Bundler sorts out dependencies and installs missing gems or matches up gems with the right versions based on gem dependencies.

## Big Title 2

You can also use Docker to directly build and run the site on your local machine. Just clone the repo and run the following from your working dir:
```
docker-compose build --no-cache && docker-compose up
```
The site should now be running at [http://localhost:4000/](http://localhost:4000/).

This is perhaps the easiest way to see how your site would actually look.


{% include links.html %}
