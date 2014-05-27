---
layout: post
title: "Redeployment Spotlight Ohana API"
date: 2014-05-25 21:05:58 -0400
comments: true
categories: "Redeployment"
Author: Wryen Meek
---

{% img https://googledrive.com/host/0ByZDjdeJ4Y3SamhBVWlYdFljcWc/ohanaapi.png %}

# Application Details

[API GitHub Repository](https://github.com/codeforamerica/ohana-api)  
[Admin Site Repository](https://github.com/codeforamerica/ohana-api-admin)
[Open Referral Data Model](https://github.com/codeforamerica/openreferral/blob/master/openreferral.md)
[Search Site](https://github.com/codeforamerica/ohanakapa-ruby)

Live Sites:  

   * [API](http://ohana-api-demo.herokuapp.com/api)
   * [Admin](http://ohana-api-admin-demo.herokuapp.com/)
   * [Data Model](https://github.com/codeforamerica/openreferral/blob/master/openreferral.md)
   * [Search (site users would interact with)](http://www.smc-connect.org/)
   * [SMS interface](https://github.com/marks/ohana-sms)

[Concept and Use Video](http://www.youtube.com/watch?v=KLXZ4nGJkYc)  

# What is it?

The [Ohana API](http://ohanapi.org/) is an open directory of social services. The API itself is a database and set of commands (Aplication Programming Interface or API) that allows the database to be changed in a standardized way. It comes with and Admin Site to permit organizations to update their own information. It also comes with a Search Site to consume the API data and display the information to users. The whole thing is based on the Open Referral Data Model. There is also an SMS interface powered(Relevant Links above)

# Evaluation for Greenville
## 1. **Will this App be helpful to the citizens of greenville?**

  * It would be very helpful to the citizens using county or non profit social services to navigate a complete system.
  * It would be helpful to social service case workers guiding individuals and families thought the assistance landscape.
  * It would be helpful to greenville county non profits to know which orgnaizations to get users from and which organizations to send users to once their mission is complete.

## 2. **Will the citizens of greenville use this application?**  

 If citizens know about it and need the services they are likely to use it. The key will be on-boarding social service organizations and teaching their staff to use the search site in their day to day workflow. Once the service organizations are using it and sharing it with their constituents are likely to follow suit. We will need to educate common public internet access points like the county libraries that the site exists and how to use it.

## 3. **Has the App been re-deployed by another brigade?**  
 No

## 4. **What are the technical depedencies?**  

#### API Dependencies

 * PostgresDB
 * Human Services Data Specification
 * Ruby version 2.1.1
 * Rails version 4.0.4
 * Redis
 * API framework: Grape
 * Testing Frameworks: RSpec, Factory Girl, Capybara
 * [OSX VM](https://github.com/codeforamerica/ohana-api-dev-box)
 * Heroku Deployment

#### Admin Site Dependencies

 * Ruby version 2.1.1
 * Rails version 3.2.16
 * MongoDB with the Mongoid ORM
 * Testing Frameworks: RSpec, Factory Girl, Capybara
 * Heroku Deployment

#### Search Site Dependencies

 * Ruby version 2.1.1
 * Rails version 4.0.4
 * Template Engines: ERB and HAML
 * Testing Frameworks: RSpec, Capybara and capybara-webkit
 * OSX and Linux Deployment Options

#### SMS Interface Dependencies
 * Ruby (version?)
 * Heroku Deployment
 * [Tropo](https://www.tropo.com/)

## 5. **How much does it cost to deploy and maintain?**  

Unknown. We might be able to run the entire suite on a docker server and keep it pretty cheap. We need to chat with the SMC site maintainers to get a better idea of how the application scales with use. The SMS component might have additional usage fees via the Tropo service.

## 6. **What are the data dependencies?**

There are no civic data dependencies. Greenville County and City services could be added at anytime. Municipal partners could be trained to update their own information or an annual civic write-a-thon event could be held to update the information on behalf of the city.

## 7. **How can we contribute or improve the app if we deploy it?**  

 A community guide to redeployment and a streamlined Docker deployment process would be very helpful.
