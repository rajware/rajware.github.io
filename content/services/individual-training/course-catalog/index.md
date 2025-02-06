---
title: 'Course Catalog'
date: 2025-02-06T13:17:00+05:30
draft: false
onelinesummary: "Course catalog"
weight: 40
topsectionclass: 
---
|Course||Duration|
|---|:---:|---:|
|Understanding Containers||4 hours|
|Building Container Images||4 hours|
|Building Container Images for .NET||2 hours|
|Building Container Images for Node.js||2 hours|
|Building Container Images for Go||2 hours|
|Understanding Orchestration||8 hours|
|Designing Orchestrable Applications||4 hours|
|Designing Orchestrable Applications for .NET||2 hours|
|Designing Orchestrable Applications for Node.js||2 hours|
|Designing Orchestrable Applications for Go||2 hours|
|Understanding Helm Charts||2 hours|

```mermaid
flowchart LR
C0[Understanding Containers]
C1[Building Container Images]
C1.1(Building Container Images for .NET)
C1.2(Building Container Images for Node.js)
C1.3(Building Container Images for Go)
O0[Understanding Orchestration]
O1[Designing Orchestrable Applications]
O1.1[Designing Orchestrable Applications for .NET]
O1.2[Designing Orchestrable Applications for Node.js]
O1.3[Designing Orchestrable Applications for Go]
C0 --> C1
C1 --> C1.1
C1 --> C1.2
C1 --> C1.3
O0 --> O1
O1 --> O1.1
O1 --> O1.2
O1 --> O1.3
H0[Understanding Helm Charts]
C0 --> O0
O0 --> H0
C1 --> O0
O1 --> H0
```

How to plan your technology foundation?
Quite simple, just follow the flowchart.
The courses are designed to be building blocks in understanding the devops lifecycle.

For example, if you are a Node.js developer and are looking at building and packaging applications, you would start with signing up for Understanding Containers <Insert code link here>, then learn Building Container Images for Node.js. To learn deploying, you are required to start with Understanding Orchestration and then move to Designing Orchestratble Applications for Node.js and finally learn Understanding Helm Charts.

If you are not a developer?
Still, follow the flowchart.
The course flow is planned to help non-developers such as architects, system administrators and anyone managing application deployments.

For example, if you are a system administrator and are required to manage deployment of your in-house or client applications, you would start with Understanding Containers, then learn Understanding Orchestration and finally, Understanding Helm Charts.

Why should you choose our trainings?


What sets this set of trainings apart from others?