---

title: 'Cockpit'
layout: "section-list"
weight: 120

menu:
  main:
    identifier: "user-guide-cockpit"
    parent: "webapps"
    pre: "Web application for monitoring and operations"

---


Camunda BPM Cockpit is a web application for monitoring and operations. It provides access to deployed BPMN processes, CMMN cases, DMN decisions and deployments. It allows searching though running and ended instances and performing operations on these. Furthermore, you can access reports, find details about human tasks and batches and perform batch operations.

{{< img src="img/dashboard.png" title="Cockpit Dashboard" >}}

The Cockpit architecture is extensible, allowing it to be extended through [plugins][cockpit-plugins].

[cockpit-plugins]: {{< relref "webapps/cockpit/extend/plugins.md" >}}
