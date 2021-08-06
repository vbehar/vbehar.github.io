---
title: "Jenkins X"
date: 2018-09-01
featured: true
description: "I made plenty of contributions to Jenkins X and all its components, including bug reports, bug fixes, new features, and promotion through blog posts and talks."
tags: ["Jenkins X","Kubernetes","Go"]
image: "/img/oss-project-jenkins-x.png"
link: "https://jenkins-x.io/"
weight: 500
sitemap:
  priority : 0.8
---

[Jenkins X](https://jenkins-x.io/) is a CI/CD platform on top of [Kubernetes](https://kubernetes.io/). I started using it while it was still a young project, in september 2018.

I made various contributions:
- code, of course - including bug fixes and new features
- documentation and blog posts on the [Jenkins X blog](https://jenkins-x.io/blog/)
- support on the [community Slack channels](https://jenkins-x.io/community/#slack)
- demos at [Office Hours](https://jenkins-x.io/community/office_hours/) - see [recordings on YouTube](https://www.youtube.com/playlist?list=PLr_PmC4W69dIdqUUy-PAitbkqsujNLBf1)
- talks at conferences and meetups, and interviews on podcasts
- ...

I also got a few awards, such as:
- **Most Valuable Jenkins X Contributor** at the [2021 Continuous Delivery Foundation Community Awards](https://cd.foundation/blog/2021/06/25/continuous-delivery-foundation-announces-2021-cdf-community-awards-winners/) - see the [video on YouTube](https://youtu.be/ZYEfJrKc8ig?t=228)
- **Most Innovative Jenkins X Implementation** at the [2019 Jenkins Community Awards](https://www.cloudbees.com/press/2019-devops-world-jenkins-world-award-winners-announced) - see the [video on YouTube](https://youtu.be/U-fI_-in6Lo?t=593)

I'm a maintainer on a few Jenkins X components:
- the [Jenkins X Pipelines Visualizer](https://github.com/jenkins-x/jx-pipelines-visualizer) - a webui to visualize the pipelines and their logs
- the [Lighthouse WebUI Plugin](https://github.com/jenkins-x-plugins/lighthouse-webui-plugin) - a webui to visualize webhooks events, Lighthouse jobs, merge status and history
- [Jenkins X Release Version](https://github.com/jenkins-x-plugins/jx-release-version) - a simple binary to calculate the next release version
- everything observability-related, including:
  - [Lighthouse Telemetry Plugin](https://github.com/jenkins-x/lighthouse-telemetry-plugin) - to produce distributed traces for pipelines and gitops workflows
  - [Continuous Delivery Indicators for Jenkins X](https://github.com/jenkins-x/cd-indicators) - to collect various metrics, store them, and display them through Grafana dashboards
  - [Grafana Dashboards](https://github.com/jenkins-x-charts/grafana-dashboard) - a set of Grafana dashboards for the Jenkins X platform
