---
type: rule
archivedreason: 
title: Do You Tell People the Coding Standards You Expect?
guid: d4108bfb-2d82-429f-b2d5-880b18b5c5f4
uri: do-you-tell-people-the-coding-standards-you-expect
created: 2016-03-28T19:54:30.0000000Z
authors:
- id: 24
  title: Adam Stephensen
related: []

---

The code within your solution should be consistent. (We all know that)

In an open source project the easy way to ensure that all developers share and are aware of the expectations is to include and ENGINEERING-GUIDELINES.md markdown file that includes important technical considerations like:

<!--endintro-->



* Copyright header requirements
* Approved external dependencies
* Coding guidelines and standards
* Source control requirements
* Branching strategy
* Solution and project folder structure and naming
* Unit testing requirements

<dl class="image">&lt;dt&gt;<img src="guidelines-opensource.png" alt="guidelines-opensource.png" style="width:600px;height:660px;">&lt;/dt&gt;<dd>Figure: Good Example - Adding an ENGINEERING-GUIDELINES.md to your project clearly defines the engineering practices and guidelines that must be required for contributors pull requests to be accepted</dd></dl>