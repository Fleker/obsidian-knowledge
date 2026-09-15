---
layout: "default"
title: "OPSO Book"
---
OSPO Book

Defining an OSPO An OSPO is designed to do the following:
1. Be the center of competency for an organization’s open source operations and structure, and 2. Place a strategy and set of policies on top of an organization’s open source efforts. 
This can include setting code use, distribution, selection, auditing, and other policies; training developers; ensuring legal compliance; and promoting and building community engagement to benefit the organization strategically.

*****

• Building Healthy Relationships with Key Open Source Projects: Commercial organizations that are using open source are often keen to contribute back to the projects they use. However, the pressure to ship features in their own products means that open source contributions may take a back seat when things get busy. Even when it’s known that contributing features and bugfixes to upstream is less effort in the long term than to maintain a fork of the project, organisations often optimize for short term benefits and don’t spend the extra effort to upstream the changes.

*****

Public sector organizations face unique challenges when it comes to managing their open source operations, including the need to comply with strict laws and regulations, and the requirement to provide transparent and accountable operations. An OSPO can help governments and public sector organizations to overcome these challenges.

*****

Improving Service Delivery: An OSPO helps to improve the delivery of public services, by enabling them to adopt innovative and cost-effective technologies, and to collaborate with external stakeholders to develop better solutions. This helps organizations to provide better services to citizens and to meet the changing needs of their communities.

*****

The answer depends on how you view the OSPO. Beyond the multiple different structures an OSPO can have, it’s fundamentally about its people. An OSPO is a group of open source subject matter experts providing support, knowledge, and management related to all open source activities. These people must be not only retained but also reinforced and effectively financed for the future, as more open source integration is inevitable.

*****

Getting a clear view of what open source components are in the commercial software you buy or services you use. Ask vendors for what OSS they use, for example by requesting Software Bill of Materials (SBOMs).

*****

The OSPO Japan Local Meetup Working Group, supported by the TODO Group and OpenChain, has been developing a simple Frequently Asked Questions (FAQ) guide about OSPOs. This guide aims to answer questions at each step of the OSPO maturity model, which categorizes different open source activities from stage 0 to 4, and outlines the role of the OSPO at each level.

*****

While planning the OSPO it’s very helpful have 1:1 conversations with managers, high-level executives, and workers/contractors from different teams that use open source in their day-to-day operations, or whose strategy involves dealing with open source projects (in terms of licenses, security vulnerabilities). Use the insights from these conversations to define the organization’s unique motivators and map them to areas within the organization where open source brings value.

*****

Managers (of both open and closed source projects) should understand how to manage secure software development. This includes knowing basic security terms, how to manage risks, how to build security into the design, how to protect all environments, how to identify risks early, and how to set clear expectations with stakeholders. Managers should also understand what their developers need to learn. If they haven’t been trained yet, they can take the free Open Source Security Foundation OpenSSF course Security for Software Development Managers (LFD125)1.

*****

Developers should take a course on secure software development. This includes how to build secure software during planning, design, coding, testing, and release. Developers also need to know how to evaluate third-party software. They should understand common vulnerabilities (like those in the OWASP Top Ten for web apps2 and CWE Top 25 for general software3) and how to avoid them. They should also know how to secure development environments and respond to vulnerability reports. If they haven’t had this training, they can take the free OpenSSF course Developing Secure Software (LFD121)4.

*****

For example, instead of running security checks only once in a while, make tools like scorecards and vulnerability scans part of your regular CI/CD pipeline. This helps make security a normal and expected part of how your team builds software.

*****

The CHAOSS project (Community Health Analytics for OSS) advocates for using the “goal-question-metric” because it’s a structured method for deriving metrics that align with organizational goals. It involves three key steps:
Goals Identify and understand your organizational goals. These can vary significantly but typically include objectives like recruiting talent or enhancing community engagement.
Questions Break down these goals into specific, actionable questions. For example, to assess recruitment efforts, one might ask, “Who are important contributors?” or “How many did we help hire?”
Metrics Develop metrics to answer these questions. Metrics should be operational and data-driven, such as the number of contributions by name, hiring successes, or project activity levels. Some good data points, like the number of commits (on a software project), may not be relevant to the question you need to answer.
