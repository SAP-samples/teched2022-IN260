[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2022-IN260)](https://api.reuse.software/info/github.com/SAP-samples/teched2022-IN260)

# IN260 - Achieve Exactly-Once Semantics in Apache Kafka Using SAP Integration Suite

## Description

Learn how to build an end-to-end event-driven integration scenario where you react and respond to business events using Apache Kafka and SAP Integration Suite to deliver and process a message at the receiver system exactly once.  

## Overview

This session introduces attendees to new features that have been recently shipped in the Cloud Integration capability of SAP Integration Suite via an end-to-end integration scenario. In particular, we focus on the Kafka adapter to be able to implement pub/sub scenarios and new flow steps such as the idempotent process call that allows you to implement Exactly Once message delivery.

Check out the following chapters to understand the overall integration scenario that is handled in this exercise:

- [Scenario Introduction](intro/intro1)
- [New hire event configuration in SAP SuccessFactors (for your information only)](intro/intro2)
- [Pre-deployed Integration Flow to publish events to Confluent Kafka (for your information only)](intro/intro3)

## Requirements

There are no prior requirements to this exercise. You can perform this even if you do not have any experience with integration platform from SAP. However, you will be able to derive increased value from this session if you have some knowledge on what SAP Integration Suite is all about and how it helps with enterprise-wide integration needs.

You can check out this SAP Discovery Center mission that will help you in getting started with SAP Integration Suite:
- [Get Started with Integration Suite - Cloud Integration](https://discovery-center.cloud.sap/protected/index.html#/missiondetail/3258/3327/)

## System logon & user information

For running through the exercises, we will provide access to the following systems:
- [SAP SuccessFactors system](https://salesdemo4.successfactors.com/login?company=SFPART038010)
- [SAP Integration Suite tenant](https://teched-us01.integrationsuite.cfapps.us10-002.hana.ondemand.com/)
- [Confluent Kafka system](https://confluent.cloud/login/sso/sap-is-ias)
- [SAP Build Process Automation - Task Center](https://teched-2022-in260-tk4694cz.sap-process-automation.cfapps.us10.hana.ondemand.com/comsapspaprocessautomation.comsapspainbox/inbox.html)

User and password information will be provided to you by the instructors.

When you run through the exercise steps, you need to ensure that the technical IDs of the integration artifacts that you will create are unique. Hence, add a participant number to your integration artifacts. The participant number will be assigned to you by the instructors.

## Exercises

In the following, the complete list of exercise steps are listed. Run through them in the given order. You can use this section as an index or table of contents. Use the breadcrumb navigation on top of the pages to go back to the Table of Contents.

- [Exercise 0 - Create a Kafka topic](exercises/ex0/)
- [Exercise 1 - Copy, configure and deploy the Welcome Email subscription flow](exercises/ex1/)
    - [Create a package](exercises/ex1/ex11)
    - [Copy the template integration flow](exercises/ex1/ex12)
    - [Configure and deploy your integration flow](exercises/ex1/ex13)
    - [Check the deployment status](exercises/ex1/ex14)
- [Exercise 2 - Create the SAP Build Process Automation (SPA) Approval subscription flow](exercises/ex2/)
    - [Create a new integration flow](exercises/ex2/ex21)
    - [Maintain the Kafka connection](exercises/ex2/ex22)
    - [Maintain the Content Modifier](exercises/ex2/ex23)
    - [Maintain the Message Mapping](exercises/ex2/ex24)
    - [Model the Exactly Once connectivity to SPA](exercises/ex2/ex25)
    - [Deploy your integration flow](exercises/ex2/ex26)
- [Exercise 3 - Test the integration scenario](exercises/ex3/)
    - [Add a new employee](exercises/ex3/ex31)
    - [Check the Kafka monitoring](exercises/ex3/ex32)
    - [Check the Cloud Integration monitoring](exercises/ex3/ex33)
    - [Check your Email inbox](exercises/ex3/ex34)
    - [Approve the new hire in SAP Build Process Automation](exercises/ex3/ex35)
- [Exercise 4 - Rerun the scenario with same event](exercises/ex4/)
    - [Replay the event in Kafka](exercises/ex4/ex41)
    - [Check the Cloud Integration monitoring](exercises/ex4/ex42)
    - [Check your Email inbox](exercises/ex4/ex43)
    - [Check the SAP Build Process Automation](exercises/ex4/ex44)
    - [[Optional] - Replay again with trace switched on](exercises/ex4/ex45)
    
## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt)
