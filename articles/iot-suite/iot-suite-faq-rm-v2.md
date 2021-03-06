---
title: Remote Monitoring solution accelerator FAQ | Microsoft Docs
description: Frequently asked questions for Remote Monitoring solution accelerator
services: iot-suite
suite: iot-suite
documentationcenter: ''
author: dominicbetts
manager: timlt
editor: ''

ms.assetid: cb537749-a8a1-4e53-b3bf-f1b64a38188a
ms.service: iot-suite
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 02/15/2018
ms.author: dobett

---
# Frequently asked questions for Remote Monitoring solution accelerator

See also, the general [FAQ](iot-suite-faq.md).

### How much does it cost to provision the new remote monitoring solution?

The new solution accelerator offers two deployment options:

* A *basic* option designed for developers looking for lower development cost or customers looking to build a demo or proof of concept.
* A *standard* option designed for enterprises wanting to deploy a production-ready infrastructure.

### How can I ensure I keep my costs down while I develop my solution?

In addition to providing two differentiated deployments, the new remote monitoring solution has a setting to enable or disable all the simulated devices on demand. Disabling the simulation reduces the data ingested in the solution and, thus, the overall cost.

### What is the difference between the basic and standard deployment options? How do I decide between the two deployment options?

Each deployment option responds to different needs. The basic deployment is designed to get started and develop PoC and small pilots. It provides a streamlined architecture with the minimum necessary resources and a lower cost. The standard deployment is designed to build and customize a production-ready solution, and provides a deployment with the necessary elements to realize that. For reliability and scale, application microservices are built as Docker containers and deployed using an orchestrator (Kubernetes by default). The orchestrator is responsible for deployment, scaling, and management of the application. You should choose an option based on your current needs. You might use one, the other, or a combination of both depending on your project stage.

### How do I configure a dynamic map on the dashboard?

For more information, see [Upgrade map key to see devices on a dynamic map](https://github.com/Azure/azure-iot-pcs-remote-monitoring-dotnet/wiki/Developer-Reference-Guide#upgrade-map-key-to-see-devices-on-a-dynamic-map).

### Next steps

You can also explore some of the other features and capabilities of the IoT solution accelerators:

* [Explore the capabilities of the remote monitoring solution accelerator](iot-suite-remote-monitoring-explore.md)
* [Predictive Maintenance solution accelerator overview](iot-suite-predictive-overview.md)
* [Connected Factory solution accelerator overview](iot-suite-connected-factory-overview.md)
* [IoT security from the ground up](securing-iot-ground-up.md)