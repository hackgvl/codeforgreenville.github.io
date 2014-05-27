---
layout: post
title: "Redeployment Spotlight CKAN"
date: 2014-05-25 21:06:17 -0400
comments: true
categories: "Redeployment"
author: Wryen Meek
---

{% img https://googledrive.com/host/0ByZDjdeJ4Y3SamhBVWlYdFljcWc/ckan.png %}

# Application Details

[GitHub Repository](https://github.com/okfn/ckan#sthash.sdB744rs.dpuf)  

Live Sites:  

   * [US Government Data Portal](http://www.data.gov/)
   * [UK Government Data Portal](http://data.gov.uk/)
   * [City of Denver Data Portal](http://data.denvergov.org/)
   * [US Department of Health and Human Services Data Portal](http://healthdata.gov/)
   * [City of Huston Data Portal](http://data.ohouston.org/)
   * [Demo Site](http://demo.ckan.org/)

[Concept and Use Video](http://vimeo.com/78249419)  

# What is it?
Comprehensive Knowledge Archive Network (CKAN) is a web-based open source data management system for the storage and distribution of data, such as spreadsheets and the contents of databases. It is maintained by the [Open Knowledge Foundation](http://us.okfn.org/). It uses its internal model to store metadata about the different records, and presents it on a web interface that allows users to browse and search this metadata. It also offers an API that allows third-party applications and services to be built around it.

# Evaluation for Greenville
## 1. **Will this App be helpful to the citizens of greenville?**  

Only indirectly. This application could be deployed by any city who wishes to launch their own data portal. It makes it much simpler for the community to build applications based on the data stored on it.  

## 2. **Will the citizens of greenville use this application?**  

This application is most useful to application developers, researchers, journalists, educators and businesses with an interest in civic data.  

## 3. **Has the App been re-deployed by another brigade?**  
Yes. Open Oakland and Code for DC have deployed it for their cities.

## 4. **What are the technical depedencies?**  
 * Python backend
 * Javascript frontend
 * Pylons web framework
 * SQLAlchemy ORM
 * PostgreSQL
 * SOLR search
 * modular architecture that allows extensions to be developed

## 5. **What are the data dependencies?**

There are no data dependencies for this application.

## 6. **How much does it cost to deploy and maintain?**

Unknown. As a Portal for the Brigade hosting is likely minimal. OKFN offers hosted solutions from a variety of partners for city and national level portals so we can likely get a decent estimate from them when it comes time to deploy it for a local city.

[Datahub.io](http://datahub.io/) is a web service based on CKAN which is community owned and driven. Not all of the CKAN functionality is available but it is free.


## 7. **How can we contribute or improve the app if we deploy it?**

The project has an [extensive roadmap](http://ckan.org/developers/roadmap/) we could contribute toward.
