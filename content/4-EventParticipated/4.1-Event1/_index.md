---
title: "Event 1"
date: 2026-07-07
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---


# Report: “AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY”

### Event Purpose

-   Update practical trends in Cloud Computing and methods for applying Generative AI (GenAI) within enterprise environments.
-   Share best practices for platform software architecture design, building multi-agent systems, and network infrastructure security.
-   Create a networking space for the IT community, inspiring and guiding the skill sets required for engineers in the AI era.


### Speaker List

-   **Nguyễn Gia Hưng** - Solutions Architect, AWS Vietnam (Founder FCAJ)
-   **Tinh Truong** - Platform Engineer, GoTymeX
-   **Anh Pham** - Cloud Consultant, G-AsiaPacific Vietnam
-   **Thinh Nguyen** - DevOps Engineer, FCAJ
-   **Uyển Lê, Thảo Nguyễn, Mai Nguyễn** - GenAI Engineers, VIB
-   **Duc Dao** - Solutions Architect, Cloud Kinetics
-   **Vy Lâm** - Senior Business Systems Analyst, VPBank


### Key Highlights

#### Job Trends & IT Engineer Mindset:
AI advancements lower the cost barriers of software development, triggering an explosive surge in product demand. Engineers must understand business use cases and showcase practical products to prove competence rather than relying solely on theory.
#### Context Optimization in AI:
To prevent AI from generating garbage responses (hallucinations), engineers must feed specific context and limit information rather than blindly stuffing general internet documents (the "Internet Builder" syndrome).
#### Automation with Amazon Q (AI Agent):
Applying virtual assistants to analyze Excel files, create BI dashboards, and automate meeting summaries by connecting workplace ecosystems via MCP (Model Context Protocol).
#### Network Architecture and Security with Amazon CloudFront:
Introducing Flat-rate pricing solutions to help enterprises prevent "bill shock" risks (abrupt cost spikes from abnormal traffic or DDoS attacks). Utilizing AWS Point of Presence (PoP) edge network to disperse traffic and protect the origin infrastructure using VPC Origin, enabling direct connections from CloudFront to private subnets while hiding systems from the public internet.
#### Hands-on Hackathon Experience & GenAI Product Development (UTM Morpo):
Sharing the journey of building a User Interface (UI) generation project within 36 hours using a Serverless architecture coordinated by 3 AI Agents. The team resolved time and token consumption bottlenecks caused by making AI regenerate entire UIs by developing a feature allowing direct editing of components and CSS straight on the interface. From there, the team deduced risk management lessons when using AI (running out of tokens, generating redundant code) and strategies focusing on core features instead of stuffing ideas.
#### Controlling LLM Determinism:
Explaining LLM working mechanisms and analyzing the reality that even when setting Temperature = 0, output results can sometimes fluctuate due to hardware limitations (GPU) and provider inference optimization mechanisms. Therefore, mitigation strategies are required, such as running multiple times for majority voting, self-hosting models, using JSON mode, and especially designing flexible downstream services to handle random AI errors.
#### Designing Enterprise-Grade Multi-Agent Systems:
Building a system of multiple specialized AI agents cooperating to evaluate startup business credit. This process strongly prioritizes Enterprise Security & Compliance factors by controlling MCP attack vectors, preventing Prompt Injection, building audit trails, and establishing API Key Rotation procedures.


### What Was Learned

- **Business-Driven Technical Mindset:** 
Always approach problems from business use cases and practical user experience. Breaking systems down into AI Agents or focusing on solving a core pain point completely (such as the UI editing feature instead of continuous generation) delivers higher value.

- **Technical Architecture & Information Security:** 
Mastered methods for establishing secure checkpoints with CloudFront. The VPC Origin feature is a breakthrough step for isolating backend architectures from internet risks.

- **AI Risk Management:** 
Understood the probabilistic nature of LLMs to avoid blind trust in outputs. Always anticipate scenarios where AI hallucinates, exhausts token limits, or responds with incorrect formats to establish fallback mechanisms.


### Work Application

-   Multi-Agent Systems: Break systems down into independent agents (preference analysis, recipe searching, nutritional calculation) for more accurate personalized recommendations. 
-   Content Generation Flow Optimization: Locally update (edit) a single component when users request modifications instead of regenerating the entire recipe to save tokens. 
-   Deterministic Control: Set low temperatures and force JSON mode so returned data (dish names, ingredients, instructions) always conforms to standards. 
-   Security & Context: Use CloudFront and VPC Origin to protect databases. Pass limited context (only sending ingredients currently possessed by the user) into prompts to prevent Prompt Injection. 


### Event Experience

Participating in the **“AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY”** event was a rewarding experience, providing a comprehensive view of how to combine AWS Cloud services with the power of Generative AI to build secure, stable applications. Key highlights include:

#### Learning from High-Expertise Speakers

-   Experts and engineers from AWS, VIB, GoTymeX, and Cloud Kinetics shared valuable hands-on experiences in designing and developing modern software.
-   Through practical case studies (such as the 36-hour hackathon challenge or the startup credit rating system), I gained a deeper understanding of applying Multi-Agent architectures to solve complex business workflows instead of relying solely on a single model.


#### Practical Technical Experience

-   Gained deep analysis into LLM operational mechanisms, helping me understand why AI hallucinates and how Temperature parameters and JSON mode impact output data consistency.
-   Clear visualization of network infrastructure security processes using Amazon CloudFront and VPC Origin to isolate critical backends, protecting systems from DDoS attacks or "bill shock" cost exhaustion risks.
-   Grasped the concept of MCP (Model Context Protocol) and associated security risks such as Prompt Injection or MCP Attack Vectors when granting AI permissions to interact with systems.

#### Key Takeaways
-   Breaking AI processing flows into specialized agents helps minimize errors, enhances scalability, and simplifies system debugging.
-   Never blindly trust AI results. Apply control strategies (such as running multiple times for voting) and design systems with fallback scenarios when AI returns erroneous data.
-   Security is vital when deploying GenAI applications into production. Limiting infrastructure access via CloudFront/VPC Origin and establishing API Key Rotation procedures are mandatory compliance standards.

#### Event Photos
* Add your event photos here

![Event 1](/images/4-Event/Event1_1.jpg)
![Event 1](/images/4-Event/Event1_2.jpg)