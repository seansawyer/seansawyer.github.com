---
title: Home
layout: default
---

## Contact ##

[Github][github]

[Instagram][instagram]

[github]: https://github.com/seansawyer
[instagram]: https://instagram.com/seanakadug


## Education ##

BS in Computer Science, December 2002, University of Georgia


## Qualifications ##

I love to build data-heavy applications, most often using Python, Java and
sometimes Scala. Under the hood of the things I've built in recent memory
you'll also find Elasticsearch, Kafka, PostgreSQL, Redis.

In the past, I've built distributed systems with Erlang and web applications
with PHP and Ruby.

Although it hasn't been my primary focus, I've also done a decent amount of
devops along the way - on bare metal, managed hosting, AWS and GCP - and have
worked with both Puppet and Chef.


## Professional Experience ##

__Senior Software Engineer__ at
[MailChimp][mailchimp]

May 2012 to present

Throughout my time at MailChimp, my efforts have focused on turning our data
scientists' research into production services that empower small organizations
and businesses by putting the power of analytics and statistical modeling within
their reach.

* Designing and leading development of MailChimp's data pipeline, which
  streams billions of row-level changes each day from the binlogs of our
  hundreds of MySQL instances. The underlying triptych of Scala applications
  produces Kafka topics representing each change as a Thrift-serialized struct.
* Creating and maintaining client libraries and tooling related to MailChimp's
  data pipeline, variously in Java, PHP and Python.
* Designing and building MailChimp Pro's reporting and segmentation service
  using Scala, PHP, PostgreSQL and Redis.
* Designing and building MailChimp's predictive analytics service using Python,
  R, Redis and RabbitMQ. The service maintains summary statistics on
  around 4 billion unique email addresses, which feed models for predicting
  bounce rates, optimizing campaign send times, and detecting bots.
* Prototyping MailChimp's predictive demographics service, as well as
  a BI tool enabling customers to perform ad hoc analysis on their MailChimp
  data using Python and BigQuery.
* Contributing to the development of MailChimp's in-house web framework,
  including improvements to its ORM, process management, and concurrency APIs.
* Collaborating across a wide array of teams to facilitate access to data
  for stream and batch processing.

[mailchimp]: https://mailchimp.com

__Staff Engineer__ at
[Vitrue][vitrue]

July 2010 to May 2012

As a lead developer on Vitrue’s Core Services team, I focused heavily on
modularizing and scaling the core APIs behind Vitrue’s social marketing
platform.

* Developed a social data harvesting/notification service and caching API
  using Erlang, ZeroMQ, Redis and PostgreSQL. This distributed system replaced
  a slower, more limited Ruby application, realizing substantial performance
  and reliability gains.
* Led development of Vitrue Publisher's conversational features
  for Facebook and Twitter using Ruby, Rails and MongoDB.
* Prototyped Vitrue’s location-based marketing offering: a self-service toolkit
  with Foursquare and Facebook Places integration, also built using Ruby, Rails
  and MongoDB.
* Collaborated with other members of the team on devops-focused efforts,
  building and maintaining Vitrue’s EC2 infrastructure using Chef and Scalr.
* Mentored junior engineers via frequent pair-programming and code review
  sessions, as well as organizing reading groups.

[vitrue]: http://www.oracle.com/us/solutions/social/vitrue/index.html


__Senior Software Engineer__ at
Mobilization Labs

May 2008 to July 2010

At Mobilization Labs, I helped drive development of Wildfire Platform, a
SaaS web application used by primary by non-profits to manage and mobilize
their supporters for grassroots action. The application was used by a diverse
crowd of organizations, from the National Urban League, to the Atlanta Mission,
to even the Jonas Brothers. Wildfire was built using Java, Spring and
PostgreSQL.

* Led development of the platform’s REST API and implemented a number of client
  applications powered by the API, including a live SMS survey application
  written in Scala, and a number of smaller-scale PHP solutions.
* Created and maintainted a load testing suite (using Tsung) simulating common
  traffic patterns within the application based on analysis of access logs from
  periods of heavy production load.
* Collaborated with other engineers in scaling the platform, including the
  integration of Terracotta for clustered heap and S3/Cloudfront for asset
  delivery.

__Senior Software Engineer__ at
[InComm][incomm]

January 2008 to May 2008

I helped guide the growth of InComm’s web development team by by agitating for
improved development practices, mentoring other developers, and leading a range
of improvements across the gaggle of web applications owned by this small team.

* Designed and implemented a half-dozen new web applications (some internal,
  some user-facing) using Java and Spring, while supervising a team of five
  engineers. I also designed the UI for several of these applications, for
  better or for worse!
* Planned and implemented a number of much-needed improvements to existing
  production applications on a variety of platforms (Ruby/Rails, Java/Spring,
  ColdFusion). These included UI overhauls, performance optimization and
  critical feature additions, as well as migration from Struts to Spring MVC.

[incomm]: http://www.incomm.com/Pages/default.aspx


## Odds and Ends ##

During my time at Vitrue, my employer was kind enough to let me open-source
[an Erlang ISO 8601 library][iso-8601].

Long long ago, I worked as a Java developer at [Hannon Hill][hannon-hill]
and as a sysadmin and PHP developer at a small law firm.

[hannon-hill]: https://www.hannonhill.com
[iso-8601]: https://github.com/erlsci/iso8601
