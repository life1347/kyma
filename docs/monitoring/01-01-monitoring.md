---
title: Overview
---

Kyma comes bundled with third-party applications like Prometheus, Alertmanager, and Grafana, that offer a monitoring functionality for all Kyma resources. These applications are deployed during the Kyma cluster installation, along with a set of pre-defined alerting rules, Grafana dashboards, and Prometheus configuration.

The whole installation package provides the end-to-end Kubernetes cluster monitoring that allows you to:

- View metrics exposed by the Pods.
- Use the metrics to create descriptive dashboards that monitor any Pod anomalies.
- Manage the default alert rules and create new ones.
- Set up channels for notifications informing of any detected alerts.

> **NOTE:** The monitoring functionality is available by default in the cluster installation, but it is disabled in the **Kyma Lite** local installation on Minikube. Read [here](/root/kyma/#configuration-custom-component-installation) how to enable the `monitoring` module for the local installation.
