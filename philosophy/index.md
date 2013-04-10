---
layout: default
title: Open Source Philosophy
---

<div class="hero-unit clearfix">
  <i class="icon-heart icon-4x pull-left"><!-- This space left blank --></i>
  <h1 class="tagline">Open Source Philosophy</h1>
  <p>A message from our CTO, Will Pugh.</p>
</div>

## Socrata Releases "Open Source Data Server, Community Edition"


Three months ago, we announced that Socrata has started working on an open source option we call the "Socrata Open Data Server, Community Edition." This is the core piece of our technology that powers our SaaS platform and an equally important part of our strategy to promote worldwide adoption of open data standards. I blogged about this here, and here.

Let's quickly recap why Socrata has committed to this project. 

### Our Goals for Community Edition

We're offering an open source product for a number of reasons, all related to accelerating and broadening the growth of open data. We want to: 

1. Promote data portability throughout the open data ecosystem.
2. Support open source software policies in public organizations around the globe.
3. Encourage the development of software on top of open data.

In the words of Kevin Merritt, our CEO, "Socrata is investing in an open source product because it will help us accelerate mainstream adoption of the open data cloud model as the de facto enterprise data architecture. We envision a future where the 99 percent of data still locked up in legacy proprietary systems will be open and accessible to the masses."

### What the "Community Edition" Will Offer

The "Socrata Open Data Server, Community Edition" supports the ongoing development of open data standards in three key areas, all required for a thriving ecosystem:

1. *Data Catalog Interoperability* - Enables universal federation of different open data catalogs using a standard catalog schema, based on the W3C Data Catalog Vocabulary (DCAT).
2. *Data Portability Based on Standard Data Formats* - Standardizes outputs including JSON, XML, and CSV, as well as RDF and other Linked Data standards. The goal is to evolve towards standard schemas that developers can use for popular data sets, based on real-world examples and collaboration between data publishers.
3. *Application Portability Based on Open Data API Standards* - Standardizes the Application Programming Interfaces (APIs) used to programmatically access open data, using established paradigms and protocols such as REST, HTTP, and Structured Query Language (SQL).

### What Today's Release Includes

Today, we're happy to share our initial open source release which, over the coming weeks, will mature into a full open data API server that provides: 

A free and open implementation of our SODA 2.0 API, so anyone concerned with lock-in or proprietary APIs doesn't have to worry anymore. They can setup the open source version and any third party applications using SODA 2.0 that go against Socrata can go against our open source offering, as well.
A solution to an interesting problem out there: how to create standard APIs and usage over data that can vary wildly in terms of how often it changes, how big it is, and how often it is accessed.
Code that is modular and makes it easy for other people to not only contribute code to the core project, but also to make modules for different data stores or functionality.

This initial release will take place over the next three weeks. For more details about the architecture of the "Socrata Open Data Server, Community Edition," the upcoming phases in our open source roadmap, and information on how to contribute, please visit <http://open-source.socrata.com>.  

To get a good understanding of our new SODA API, if you're not familiar with it already, look at our documentation on <http://dev.socrata.com>. Or, for a closer look at the specification and implementation of our SoQL query language, see <https://github.com/socrata/soql-reference>.

We will keep you up to date on our progress as we complete this first phase. We would love to get your feedback so please stay in touch with us we release our more code and updated documentation.
