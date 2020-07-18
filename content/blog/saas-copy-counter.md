---
title: "Word Count of SaaS sites"
subtitle: "Need insights from sales copy"
excerpt: "Writing sales copy on a SaaS website takes time. Could we get some insights from other SaaS sites? I am happy to mentor if someone is interested in building a weekend project on this"
description: "Word Count of SaaS sites"
date: 2020-07-18
author: "Bargava"
draft: false
images:
  - /blog/assets/hway.png

series:
  - weekend-hack
tags:
  - Personal
categories:
  - weekend-hack
layout: single
---

> Being approximately right at the right moment is better than being accurate after the moment has passed.

This is a fun weekend project for someone interested in doing a data science project. A problem I've been grappling with is what, how, and how much to write on the website of the SaaS product. For a SaaS company, the website is pretty much its sales [copy](https://en.wikipedia.org/wiki/Copywriting). It is interesting and relevant to know how the market, and especially the competitors, present their sales copy.

Let's start with "How much" to write. One way to quantify this is the number of words and images in each of the pages. Are fewer words ideal or should the sales copy be more? What is the industry standard currently? You could A/B test different copy lengths and see which converts more. But having a data-centric view on the current landscape before proceeding down this path might be prudent.

Here's what I have in mind.

Scrape several popular SaaS companies' websites. Most of them have similar templates. *A home page. Product page. About us. Pricing.* With a bit of cleaning, it should be easy to get some aggregate metrics and publish the results in a dashboard.

My technical stack would look something like this:

- `jupyter notebook` as the coding environment and `python` as the coding language. 
- Google Colab for development.
- Scrape websites using `scrapy` or `beautiful soup`
- `pandas`, `spacy` and `hugging face` to do text processing
- `altair` or `plotly` to build the dashboard
- `streamlit` to host the application
- Deploy this on `heroku`
- Code repo: `github` (or `gitlab` or `bitbucket` if you are already on it)
- If you want to go all fancy, you could use `fastAPI` to build and deploy the app. But that will require coding the front-end (so, you will need to know `HTML` and `CSS` - I am not going to recommend it for a weekend hack).

All of the above services are available for free. The only advice and word of caution I have are to be respectful of the [robots.txt](https://en.wikipedia.org/wiki/Robots_exclusion_standard) file in each of the sites.

I am not sure if there is a micro-SaaS that can be built out of this. Maybe there is - but I am skeptical. One could get all fancy and use more detailed NLP models from `hugging face` to extract a variety of attributes to build insights on. But that's going to take more than a weekend to do.

I am happy to help and mentor if someone is interested in building this as a weekend project.


_I typically post on startups and Machine Learning. Please follow me on [twitter](https://twitter.com/bargava) for more articles._
