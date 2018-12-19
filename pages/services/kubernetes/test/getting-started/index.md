---
layout: layout.pug
navigationTitle: Tutorial - Kubernetes on DC/OS Enterprise
title: Tutorial - Setting Up Kubernetes on DC/OS Enterprise
menuWeight: 40
excerpt: Learn how to get up and running using Kubernetes on DC/OS Enterprise
enterprise: true
---

# Learning Objectives

In this guided tutorial, you will learn many of the basics of using Kubernetes on top of DC/OS Enterprise. Specifically, you will learn the basics of how to:

  - **set up DC/OS Kubernetes on a DC/OS Enterprise cluster** including:

    * setting up the DC/OS Enterprise cluster to be able to connect to the Kubernetes command line (`kubectl`)
    * installing the Mesosphere Kubernetes Engine and CLI to create Kubernetes clusters
    * configuring and securing service accounts for MKE and each Kubernetes cluster to be created
    * configuring DC/OS Edge-LB on top of DC/OS Enterprise to connect to multiple Kubernetes clusters' api servers
    * deploying an Nginx deployment on your new cluster
    * viewing the Kubernetes dashboard

  - **demonstrate some of the valuable advantages of running Kubernetes on DC/OS Enterprise**:

    * High density (HD) Kubernetes: multiple Kubernetes clusters on a single DC/OS node
    * Dynamic scaling of Kubernetes clusters: just reconfigure and watch them scale

<p class="message-important"><strong>IMPORTANT: </strong>This tutorial assumes you have access to a production DC/OS Enterprise cluster. If you do not have DC/OS Enterprise but would still like to see what Kubernetes can do, please visit the [Quick Start Guides](/services/kubernetes/__VERSION__/quickstart/) which takes you through installing the open source version of DC/OS and installing Kubernetes together.</p>

# First Section: Installing and Using Kubernetes on DC/OS

In the [first part of the tutorial](/services/kubernetes/test/getting-started/provision-install/), you will set up your cluster for a successful installation of DC/OS Kubernetes, install the Mesosphere Kubernetes Engine (MKE), and finally create a pair of high density Kubernetes clusters using the DC/OS Kubernetes CLI.