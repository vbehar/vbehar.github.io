---
title: "Jenkins X Projects"
date: 2020-09-01
featured: true
description: "Since 2020, I started contributing more to Jenkins X by creating new components, mainly for observability - but also web UIs."
tags: ["Jenkins X","Kubernetes","Go","Open Source"]
image: "/img/oss-project-jenkins-x.png"
link: "https://jenkins-x.io/"
weight: 300
sitemap:
  priority : 0.8
---

I started using [Jenkins X](https://jenkins-x.io/) in 2018, and since then [I've been contributing to the project](/projects/contributions/jenkins-x/).

Since 2020, I started contributing more to Jenkins X by creating new components, mainly for observability - but also web UIs.

### JX Pipelines Visualizer

The first new project I created for Jenkins X was the [JX Pipelines Visualizer](https://github.com/jenkins-x/jx-pipelines-visualizer): a web UI to visualize the pipelines and their logs.

{{< tweet user="vbehar" id="1309030017079349251" >}}

{{< tweet user="vbehar" id="1351205169195847681" >}}

### Continuous Delivery Indicators

Based on our work at Dailymotion around Continuous Delivery Indicators, I created a new Jenkins X project: [CD Indicators](https://github.com/jenkins-x/cd-indicators), to:
- collect various events from both the Kubernetes API and the git provider webhooks - such as pipelines, pull requests, releases, deployments, etc.
- store these events in a PostgreSQL database
- visualize the metrics/indicators through Grafana dashboards

{{< tweet user="vbehar" id="1377893014304133120" >}}

### Lighthouse Telemetry

The [Lighthouse Telemetry Plugin](https://github.com/jenkins-x/lighthouse-telemetry-plugin) is a [Lighthouse](https://github.com/jenkins-x/lighthouse) plugin used to generate telemetry data, such as distributed traces for:
- Jenkins X pipelines
- Jenkins X gitops workflow

{{< tweet user="vbehar" id="1378010544368717829" >}}

{{< tweet user="vbehar" id="1422936575562895367" >}}

### Lighthouse WebUI

The [Lighthouse WebUI Plugin](https://github.com/jenkins-x-plugins/lighthouse-webui-plugin) is a web UI for [Lighthouse](https://github.com/jenkins-x/lighthouse) used to visualize:
- webhook events (push, comments, ...) and the related jobs triggered by each event
- lighthouse Jobs
- lighthouse Merge Status
- lighthouse Merge History
