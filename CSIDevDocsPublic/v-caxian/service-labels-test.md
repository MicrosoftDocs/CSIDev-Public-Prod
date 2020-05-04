---
title: Concepts - Kubernetes basics for Azure Kubernetes Services (AKS)
description: Learn the basic cluster and workload components of Kubernetes and how they relate to features in Azure Kubernetes Service (AKS)
services: container-service
author: adunndevster

ms.service: container-service
ms.topic: conceptual
ms.date: 06/03/2019
ms.author: adunndevster
---

# Kubernetes core concepts for Azure Kubernetes Service (AKS)

As application development moves towards a container-based approach, the need to orchestrate and manage resources is important. Kubernetes is the leading platform that provides the ability to provide reliable scheduling of fault-tolerant application workloads. Azure Kubernetes Service (AKS) is a managed Kubernetes offering that further simplifies container-based application deployment and management.

This article introduces the core Kubernetes infrastructure components such as the *control plane*, *nodes*, and *node pools*. Workload resources such as *pods*, *deployments*, and *sets* are also introduced, along with how to group resources into *namespaces*.
