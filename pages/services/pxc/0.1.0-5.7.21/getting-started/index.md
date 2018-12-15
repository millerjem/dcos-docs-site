---
layout: layout.pug
navigationTitle:
excerpt: Getting started with Percona XtraDB Cluster
title: Getting Started
menuWeight: 20
model: /services/pxc/data.yml
render: mustache
---

Getting started with a test instance of the DC/OS {{ model.techName }} service is straightforward.

## Prerequisites
<!-- What prerequisites must be fulfilled before installing a basic cluster? -->


- Depending on your security mode in Enterprise DC/OS, you may need to [provision a service account](/services/pxc/0.1.0-5.7.21/security/service-account/) before installing. Only someone with `superuser` permission can create the service account.
	- `strict` [security mode](/latest/security/ent/#security-modes) requires a service account.
	- `permissive` security mode a service account is optional.
	- `disabled` security mode does not require a service account.
<!-- - Your cluster must have at least {{ model.install.minNodeCount }} private nodes.
{{ model.install.customRequirements }} -->

#include /services/include/getting-started.tmpl