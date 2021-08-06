---
title: "Flowdock to Elasticsearch"
date: 2014-04-17
featured: false
description: "In 2014 I created a small Scala project to import data from Flowdock into Elasticsearch, so that I could play with Kibana dashboards and visualizations."
tags: ["Scala","Elasticsearch","Kibana","Flowdock","Open Source"]
image: "/img/oss-project-elasticsearch.png"
link: "https://github.com/vbehar/flowdock2es"
weight: 900
sitemap:
  priority : 0.8
---

In 2014, I wanted to play with [Elasticsearch](https://www.elastic.co/products/elasticsearch) and [Kibana](https://www.elastic.co/products/kibana), so I created a small project to import data from a [Flowdock](https://www.flowdock.com/) instance into Elasticsearch, and then build a Kibana dashboard to visualize the Flowdock usage.

It is written in [Scala](https://www.scala-lang.org/) and uses the Flowdock REST API to retrieve data, and the [Elastic4s](https://github.com/sksamuel/elastic4s) scala lib to populate the Elasticsearch index. I also [contributed to the Elastic4s open-source project](/projects/contributions/elastic4s/).

Here is a screenshot of the Kibana dashboard:

![Flowdock2es Screenshot](/img/oss-project-flowdock2es.png)

{{< tweet 456830005872709632 >}}
