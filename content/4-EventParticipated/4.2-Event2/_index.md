---
title: "Event 2"
date: 2026-07-07
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Report: “FCAJ COMMUNITY DAY - DATA DRIVEN, AI RISEN”

### Event Purpose

-   Provide a practical perspective on the AI wave shaping the future of businesses.
-   Guide how to integrate modern solutions such as Voice AI, DevOps automation, and AI in Human Resources (HR).
-   Share methods for securing internal connections when deploying AI Agent systems (via MCP protocol) on the AWS cloud.


### Speaker List

-   **Steve Tran** - CTO/Founder, CloudThinker
-   **Trung Vu** - CEO, Revve AI
-   **Nghi Danh** - AI Engineer, Renova Cloud
-   **Kiet Tran** - AI Engineer, AWS Student Builder Group
-   **Bao Phan & Nguyen Nguyen** - Cloud Engineers, Cloud Kinetics
-   **Truong Tran & Anh Dang** - AI Solution Sales, Noventiq
-   **Toan Nguyen** - AWS Security Builder


### Key Highlights

#### Career Orientation Shift:
Businesses are stopping the recruitment of basic positions and replacing them with AI or Senior personnel with excellent AI operational capabilities. Accumulating practical enterprise environment experience as early as possible is mandatory for IT students.

#### DevOps Automation & Cloud Infrastructure:
Introducing the DevOps Agent tool that helps engineers investigate Root Cause Analysis, reducing time from hours to mere minutes by self-learning system topology and exporting data via secure protocols. However, AI only recommends; humans remain the final checkpoint for executing decisions.

#### Voice AI Solutions for Vietnamese:
Solving the problem of Vietnamese data scarcity (Low-resource language). Instead of using the traditional Speech-to-Speech model, experts introduced a 3-part separated model: Speech-to-Text -> LLM logic processing -> Text-to-Speech. This method helps businesses strictly control the content AI speaks, recognize gender/regional accents, and effectively integrate Tool Calling.

#### AI Application in Human Resources (HR):
Solving personal bias and the loss of talented candidates. Utilizing Amazon Q connected directly to workplace platforms to mass-scan CVs, automatically generate JDs, compare candidate capabilities, and report expected salaries without being limited by token processing capacities.

#### Private MCP Connection Security:
To allow Amazon Q to connect to internal databases without exposing data to the Public Internet, the proposed model places the MCP Server in the VPC's Private Subnet, routing through VPC Endpoints and encrypting certificates via AWS Certificate Manager (ACM), ensuring absolute security compliance.


### Lessons & Practical Experience

#### Practical Experience
-   Witnessing incredibly impressive live demos firsthand, from a Voice Agent answering MacBook inquiries via a switchboard, and a DevOps AI automatically finding DDoS-induced system errors in moments, to Amazon Q directly analyzing CVs and scoring candidates.

#### Key Takeaways
-   AI does not steal human jobs, but people who know how to use AI will replace those who do not.
-   When building AI Agents for enterprises, security is the top priority. Data Pipelines must be established according to encryption standards, especially when interacting via internal Model Context Protocol (MCP).
-   It is necessary to integrate Multi-Agent architectures instead of Single Agents for complex systems to reduce "hallucinations", optimize Context Windows, and easily implement Role-Based Access Control (RBAC).


### Work Application

-   **Upgrade Backend for AI Recipe Finder:** Apply the VPC Connection and Private MCP Server models shared in the event to ensure API call requests from the recipe recommendation system to the Database (storing customer allergy/preference information) are completely private and not leaked to the Internet.
-   **Automated Testing and Operations:** Deploy trial DevOps AI Agent toolkits to automatically analyze logs whenever the application reports an error (e.g., failure to load a dish image), thereby reducing incident response time.
-   **Voice AI Application (Further Suggestion):** In the future, integrate a Voice AI model (Speech -> Text -> LLM finding recipe -> Text -> Speech) into the AI Recipe Finder, allowing users to cook while asking/answering recipes with a virtual assistant entirely in Vietnamese without touching the screen.


#### Event Photos

![Event 2](/images/4-Event/Event2_1.jpg)
![Event 2](/images/4-Event/Event2_3.jpg)