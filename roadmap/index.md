---
layout: default
title: Development Roadmap
---

<div class="clearfix">
  <i class="icon-road icon-4x pull-left"><!-- Delibierately left empty --></i>
  <h1 class="tagline">Development Roadmap</h1>
</div>

## Big Plans

We've got big plans for the SODA Server, Community Edition.  Instead of trying to bottle them all up, we decided to write them up as the roadmap!

### Initial Release (10 April 2013)

The goal of this release is to get the code out in the open, and describe the design and architecture.  This includes:

* All the initial projects released in Github
  * Data coordinator (missing the query coordinator piece)
  * ElasticSearch Adaptor
  * SoQL reference implementation
  * Additional supporting projects
* Architecture and design documents to show where the project is going

### SODA Server Single Coordinator Release (4-5 weeks)

This release will be the first release with a fully functional SODA stack, but will only go against a single Durable store and a single Secondary store.  This will include:

* DCAT API for getting the catalog
* Metadata will be restricted
* Truth store and Secondary stores available for Postgres and Elastic Search
* Storage restricted to single durable and single secondary store
* Drupal based user interface for viewing and managing the catalog

### SODA Server Multi-Coordinator Release (8-9 weeks)

This release will expand the SODA server to still offer a fully functional stack, but to also use several Data Coordinator instances as well as several secondary store instances. This will include:

* Configuration to manage multiple data coordinators + secondaries
* Routing layer to determine the correct data coordinator or secondary to go to

### Arbitrary Metadata Release (~4 months)

This release will add a richer set of metadata on top of data set descriptions.  This will allow users to add metadata that will be exposed through extensions of the DCAT API.

