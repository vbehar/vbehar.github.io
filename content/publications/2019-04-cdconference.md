---
title: "Our experience running Jenkins X in production"
date: 2019-04-30
pubtype: "Webinar Talk"
featured: false
description: "At the Continuous Delivery in a Cloud Native World virtual summit, I gave a talk to explain Dailymotion's reasons for selecting Jenkins X to run the ad-tech platform CI/CD pipelines, and shared our experience using it in production."
tags: ["Talk","Webinar","Jenkins X","CI/CD","Dailymotion"]
image: "/img/2019-04-cdconference.png"
link: "https://www.youtube.com/watch?v=KkGxyssqwJM"
weight: 400
sitemap:
  priority : 0.8
---

At the [Continuous Delivery in a Cloud Native World](https://cdconference.io/) virtual summit, in april 2019, I gave a talk titled **Our experience running Jenkins X in production**.

In this talk, I explained [Dailymotion](https://dailymotion.com/)'s reasons for selecting Jenkins X to run the ad-tech platform CI/CD pipelines, and shared our experience using it in production:
- how we keep our Preview Environments under control using [Osiris](https://github.com/deislabs/osiris) to scale them down to 0 when they are not used
- how we promote our releases to staging/production on different Kubernetes clusters using [Helmfile](https://github.com/roboll/helmfile) – and the benefits of it.

{{< youtube id="KkGxyssqwJM" t="80" width="600px" >}}

{{< tweet user="devopsdotcom" id="1123267185416208384" >}}
