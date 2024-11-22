---
title: "Story of Our Transition to a Custom Kubernetes Operator for an API Gateway"
date: 2023-04-20
pubtype: "Conference Talk"
featured: true
description: "At the KubeCon Europe 2023 Conference, I gave a talk to share how we transitioned to a custom Kubernetes operator for an API Gateway at Ubisoft."
tags: ["Talk","Conference","KubeCon","Kubernetes","Operator","Gateway","Kong","Ubisoft"]
image: "/img/2023-04-kubecon.jpg"
link: "https://kccnceu2023.sched.com/event/1HyYx/story-of-our-transition-to-a-custom-kubernetes-operator-for-an-api-gateway-vincent-behar-ubisoft"
weight: 400
sitemap:
  priority : 0.8
---

At the [KubeCon Europe 2023 Conference](https://kccnceu2023.sched.com/), I gave a talk titled **Story of Our Transition to a Custom Kubernetes Operator for an API Gateway**.

In this talk, I shared our challenges at Ubisoft, and why we decided to write our own Kubernetes Operator, instead of relying on existing solutions.

I explained our platform's conventions, and how we are using OpenAPI as a central point of entry for our APIs. And I detailled the features we needed - and implemented - to automatically configure our API Gateway based on the OpenAPI documents provided by the different services.

The technical stack is based on Kong, Kubebuilder/controller-runtime, testcontainers, Kind, Telepresence...

{{< youtube id="orKIKlYNzck" width="600px" >}}

{{< tweet user="vbehar" id="1649163956286631937" >}}
