---
title: "1 year with Jenkins X"
date: 2019-12-05
pubtype: "Conference Talk"
featured: false
description: "At the DevOps World | Jenkins World 2019 Conference, I gave a talk to share our experience using Jenkins X at Dailymotion for more than 1 year: how we adopted Jenkins X and its new practices – both on the organizational and technical side."
tags: ["Talk","Conference","Jenkins X","CI/CD","Dailymotion"]
image: "/img/2019-12-dwjw-lisbon.jpg"
link: "https://devopsworldjenkinsworld2019lisbo.sched.com/event/VjM0"
weight: 400
sitemap:
  priority : 0.8
---

At the [DevOps World | Jenkins World 2019 Conference](https://devopsworldjenkinsworld2019lisbo.sched.com/) in Lisbon, I gave a talk titled **1 year with Jenkins X**.

In this talk, I shared our experience using [Jenkins X](https://jenkins-x.io/) at [Dailymotion](https://dailymotion.com/) for more than 1 year: how we went from the "hello world" to the "real world" with the "most innovative Jenkins X implementation".

I explained how we adopted Jenkins X and its new practices – both on the organizational and technical side.

I did go through our custom implementation of Jenkins X:
- the integration of [Osiris](https://github.com/deislabs/osiris) in the Preview Environments, to have auto-scaling to zero deployments,
- the use of [sops](https://github.com/mozilla/sops) to encrypt/decrypt our secrets, and store them encrypted in our git repositories,
- the use of [Helmfile](https://github.com/roboll/helmfile) instead of Helm for the staging/prod deployments, to deploy on multiple clusters,
- the use of [updatebot](https://github.com/jenkins-x/updatebot) to propagate new releases as Pull Requests everywhere, and merge them when needed

Unfortunately this talk was not recorded, but you can read the related blog post: [one year with Jenkins X](/publications/2020-03-article-one-year-with-jenkins-x/).

{{< tweet user="abayer" id="1202601312111730689" >}}
