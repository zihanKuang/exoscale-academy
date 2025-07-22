---
docType: "Course"
title: "Creating SKS Cluster"
description: "Create an SKS Cluster"
courseTitle: "Creating SKS Cluster"
weight: 1
banner: "/98e16360-a366-4b78-8e0a-031da07fdacb/images/kubernetes-icon.svg"
tags: [kubernetes, exoscale, terraform, pulumi, exo-cli]
categories: [intermediate]
---

SKS (Scalable Kubernetes Service) is the Exoscale-managed cluster. To deploy an SKS cluster, we can use one of the 
following tools:

- [Terraform](https://terraform.com)
- [Pulumi](https://pulumi.com)
- [exo cli](https://github.com/exoscale/cli)
- [Exoscale Portal](https://exoscale.com)

Whatever tool we use, it creates the following resources:

- a Security Group and some associated rules
- an SKS cluster
- a Nodepool

We will go through the details of each approach, so you can select the one you prefer. But first, you need to create an account and get free credits to follow this workshop.