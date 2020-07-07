---
title: "Disrupting Enterprise Search"
subtitle: "Part 1 - Learnings from consumer search"
excerpt: "Why is it that company websites and apps don't have the same search experience as Google? What can we learn from the evolution of search to influence better search experience in Enterprises."
date: 2020-07-07
author: "Bargava"
draft: false
images:
  - /blog/assets/search-icon.png

series:
  - Startup Idea
tags:
  - startup-idea
categories:
  - Startup Idea
layout: single
---

We, human beings, are quite good at processing new information, but are _terrible_ in storing them in long-term memory(LTM). LTM is finite and very limited. Many centuries ago, the printing press took a giant step in alleviating this problem. And then, distribution boomed. The number of printed content exploded.

_Humans are a sucker for information_. How do you _find_ if the information you are searching for exist in that book? _Table of Contents_ listed the broad topic areas covered in the book. But a 300+ pages book has lot more keywords. This resulted in "_index_". Added to the end of the book, index provided a quick lookup on the word and the page(s) where it was discussed/explained.

But how to look for information amongst a number of books? This has never been solved very satisfactorily. Topic-wise arrangement in _bookstores_ and _libraries_ was one solution. This is still the most prevalent model. _Encyclopedia_ was another option - this worked as summarizing the concepts and publishing the synthesis as a meta-book (a la-book of books).

![](/blog/assets/books1.png)

## **Consumer Search**

Let's understand how search for us, as consumers on internet, evolved over the years.

#### **Consumer Search 0.1**

The internet gave rise to a new medium of writing and distributing content: _Digital_. People started writing content on their websites. Getting information from one website was easy: goto that website and the browser provided a "Find" functionality to search for a keyword. Explicit "_index_", from the book-days, were gone from the website.

#### **Consumer Search 1.0**

Web 1.0 saw a huge volume of content created in a number of websites. How to get information from various websites? A new set of internet companies called "Search Engines" came into existence. The initial set of companies crawled various websites, and indexed them on the keywords that existed in the website. Like how she used to goto library to find information, she now had to goto this search engine website - enter the term she's looking for and the search engine returns a list of websites having that word. Altavista was one of the most famous search engines in that era (mid 1990's).

#### **Consumer Search 2.0**

The search results were not very good. It was easy to game the search engine. Ordering the search results weren't great. Especially as the number of websites exploded by late 1990s, the need for a better search engine became apparent. Google, formed in 1997, came with a revolutionary approach to search. Their page rank algorithm was significantly superior to all other search algorithms at that time. And from that time on, it has managed to dominate the consumer search market. Google adapted well as Web moved to 2.0.

#### **Consumer Search 3.0**

While there are other entrants in the market right now, Google has now a huge monopoly over consumer search market. It has 80% or more market share in all leading internet markets in the world (except China). Google has consolidated its search experience by adding [Knowledge Graph](https://www.blog.google/products/search/about-knowledge-graph-and-knowledge-panels/), [personalization](https://en.wikipedia.org/wiki/Google_Personalized_Search) and using AI/ML to get better at indexing the sites and content better.

#### **Consumer Search 4.0**

We are in the cusp of Consumer Search 4.0. The Gen Z and the new set of internet users are predominantly mobile and tablet-first. And are heavily app-driven. In retail product search, [Amazon already has a leg-up over Google](https://www.retaildive.com/news/amazon-now-dominates-google-in-product-search/531822/).

Also, privacy is rapidly becoming mainstream. Niche players like DuckDuckGo, StartPage and startups like Neeva are catering to a new set of audience. DuckDuckGo is known for its privacy-preserving feature, while StartPage offers a wrapper over Google search by removing the personalization feature. Neeva plans to offer search as a subscription model, rather than the existing Ad-driven model in consumer search.

![](/blog/assets/consumer-search.png)

## **Enterprise Search**

If Gen Z indeed are using more apps than a traditional website, how does search work there? And workplace. What about workplace apps?

![](/blog/assets/biz-search.jpg)

_source [unsplash](https://unsplash.com/photos/SqsbTuo5jP0)_

This brings us to Enterprise search. A new set of companies will have to deliver the search experience for the apps and at workplace - that includes both Enterprise apps and corporate (external and internal) websites. This is a B2B play, rather than the B2C consumer search.

While the Consumer Search is fairly sophisticated, in terms of data collected, data processing and usage of AI/ML to drive better results and engagement, the enterprise search market is waiting for the disruption to happen. But first, let's understand the evolution of Enterprise search.

#### **Enterprise Search 1.0**

The most basic and rudimentary search is actually a query into the database. Since most of the data is stored in databases, it is straightforward to deliver search results by querying against appropriate database tables. This has all the challenges we saw above from Consumer Search 1.0. The ranking and in general search quality is decent at best. Another big challenge querying real-time was that the speed of search can sometimes be slow.

#### **Enterprise Search 2.0**

For a brief while, Google offered a search embed for corporate websites. Eventually Google killed this business line. The typical approach is to manually tag each of the pages(and other assets like images). The entire corpus, along with its metadata and tags are put into a specialized service like Elastic Search. And an API delivers the search results. Algolia is the market leader in this space, offering an out-of-the-box SaaS product. The current Enterprise search market is currently in this segment.

#### **Enterprise Search 3.0 ~ 4.0**

This is the space that is waiting to be disrupted. Google innovated extremely well in the 2000s to improve its consumer search offering. A similar kind of service is needed to power apps, both consumer and enterprise, as well as websites.

![crush twitter](/blog/assets/enterprise-search.png)

## **Key challenges**

- **Hetrogeneous data**: Both structured and unstructured data. Typically these include:
  - Images
  - Videos
  - Case studies
  - Fact sheet
  - Customer information from CRM
  - Pricing
  - Omni-channel touchpoints data, etc
- **Limited data**: For many companies, customer interactions in B2B are seldom at scale. Algorithms should work on "_small_" data.
- **Manual tagging**: It is heavily biased and could even be inaccurate at times. And it does not scale well.
- **Business context**: Need to embed the business and industry context. Also, it is domain dependent.
- **Privacy**: Data is proprietary and integral to a company's success. Unlike consumer search, using data across companies is typically a non-starter.

_This concludes Part 1 of the topic - which concentrated on the problem statement. <br> In Part 2, we will look into how AI/ML and better workflow management can enable a startup (or an incumbent) to address this huge market that's out there to be disrupted. We will also discuss use cases that enterprise search can empower._

Please follow me on [twitter](https://twitter.com/bargava) to get notified when I post the next article.
