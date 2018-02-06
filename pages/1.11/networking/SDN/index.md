---
layout: layout.pug
navigationTitle:  Software Defined Networks
title: Software Defined Networks
menuWeight: 4
excerpt:
enterprise: false
---

<!-- This source repo for this topic is https://github.com/dcos/dcos-docs -->


DC/OS allows UCR and Docker containers to be launched on a wide variety of Software Defined Networks (SDNs). It supports [Container Networking Interface (CNI)](https://github.com/containernetworking/cni) standard for UCR and the [Container Network Model (CNM)](https://github.com/docker/libnetwork/blob/master/docs/design.md) standard for Docker.

DC/OS comes with its own native virtual networking solution, called DC/OS Overlay, which supports both the CNI and CNM standards. 

## IPv6 support for Docker Containers
In DC/OS 1.11, DC/OS overlay has built in support for creating IPv6 networks for docker containers.

*NOTE: IPv6 support is currently available only for Docker containers and not for UCR containers.* 