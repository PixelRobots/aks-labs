---
published: true # Optional. Set to true to publish the workshop (default: false)
type: workshop # Required.
title: Advanced AKS and Day 2 Operations # Required. Full title of the workshop
short_title: Advanced AKS and Day 2 Operations # Optional. Short title displayed in the header
description: This is a workshop for advanced AKS scenarios and day 2 operations # Required.
level: intermediate # Required. Can be 'beginner', 'intermediate' or 'advanced'
authors: # Required. You can add as many authors as needed
  - "Paul Yu"
  - "Brian Redmond"
  - "Phil Gibson"
  - "Russell de Pina"
  - "Ken Kilty"
contacts: # Required. Must match the number of authors
  - "@pauldotyu"
  - "@chzbrgr71"
  - "@phillipgibson"
  - "@russd2357"
  - "@kenkilty"
duration_minutes: 180 # Required. Estimated duration in minutes
tags: kubernetes, azure, aks # Required. Tags for filtering and searching
wt_id: WT.mc_id=containers-147656-pauyu
---

## Overview

This workshop will guide you through advanced scenarios and day 2 operations for Azure Kubernetes Service (AKS). We will cover topics such as cluster sizing and topology, advanced networking and storage concepts, security concepts, monitoring concepts, and cluster update management.

---

## Objectives

After completing this workshop, you will be able to:

- Deploy and manage multiple AKS clusters
- Develop secure applications using Workload Identity on AKS
- Monitor AKS clusters using Azure Managed Prometheus and Grafana
- Manage cluster updates and maintenance.
- Manage costs with AKS Cost Analysis.

---

## Prerequisites

To complete this workshop, you will need:

- An [Azure subscription](https://azure.microsoft.com/) and permissions to create resources. The subscription should also have enough vCPU quota to create multiple AKS clusters in multiple regions. If you don't have enough quota, you can request an increase. Check [here](https://docs.microsoft.com/azure/azure-portal/supportability/per-vm-quota-requests) for more information.
- A [GitHub account](https://github.com/signup)
- Azure CLI. You can install it from [here](https://docs.microsoft.com/cli/azure/install-azure-cli). You may also want to install the aks-preview extension. You can find out how to do that [here](https://learn.microsoft.com/en-us/azure/aks/draft#install-the-aks-preview-azure-cli-extension)
- kubectl - You can see how to install kubectl [here](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- Helm - You can see how to install Helm [here](https://helm.sh/docs/intro/install/)

---

## Cluster Sizing and Topology

- Multiple clusters
- Multitenancy
- Availability Zones

---

## Advanced Networking Concepts

### Azure Container Networking Services

### Istio Service Mesh

---

## Advanced Storage Concepts

### Azure Container Storage

---

## Advanced Security Concepts

### Workload Identity

### Secure Supply Chain

- Image Integrity
- Image Cleaner

---

## Advanced Monitoring Concepts

### Azure Managed Prometheus

- ServiceMonitor
- PodMonitor

### AKS Cost Analysis

---

## Cluster Update Management

### API Server upgrades

### Node image updates

### Maintenance windows

### Azure Fleet

https://learn.microsoft.com/azure/kubernetes-fleet/update-orchestration?tabs=azure-portal

---

## Summary
