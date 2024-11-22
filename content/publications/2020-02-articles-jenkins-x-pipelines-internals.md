---
title: "Jenkins X Pipelines Internals"
date: 2020-02-03
pubtype: "Blog Post"
featured: false
description: "Series of blog posts on the internals of the Jenkins X Pipelines: Prow, Tekton, Meta-Pipeline, Stages, Steps, ..."
tags: ["Blog Post","Jenkins X","CI/CD"]
image: "/img/2020-02-articles-jenkins-x-pipelines-internals.png"
link: "https://medium.com/@vbehar/jenkins-x-pipelines-internals-fc28718562bc"
weight: 400
sitemap:
  priority : 0.8
---

While migrating pipelines from the Jenkins Declarative Syntax to the new Jenkins X YAML Syntax - built on top of Tekton - I learned a lot about the internals of the Jenkins X Pipelines, and wrote a series of blog posts to share what I learned:

- The [first part](https://medium.com/@vbehar/jenkins-x-pipelines-internals-part-1-from-github-webhook-event-to-tekton-pipeline-6927c6eb879c) is a **walk-through of a GitHub WebHook event coming to the cluster until it results in a running Tekton Pipeline**. It explains how Prow understands the webhook event, "kind of" forwards it to Jenkins X, which retrieves the right pipeline to execute and translate it into a format that Tekton can understand.
- The [second part](https://medium.com/@vbehar/jenkins-x-pipelines-internals-part-2-meta-pipeline-32bbe754294a) dives into the "**Meta Pipeline**": the part of the workflow which is responsible for retrieving the right pipeline to execute, and to translate it into a format that Tekton can understand.
- The [third](https://medium.com/@vbehar/jenkins-x-pipelines-internals-part-3-stages-f586830c775a) and [fourth](https://medium.com/@vbehar/jenkins-x-pipelines-internals-part-4-steps-cd46a4dda9d) parts are focused on the **stages** and **steps** that compose a pipeline.

You can read [the series](https://medium.com/@vbehar/jenkins-x-pipelines-internals-fc28718562bc) on Medium.

{{< tweet user="abayer" id="1223234229565382657" >}}
