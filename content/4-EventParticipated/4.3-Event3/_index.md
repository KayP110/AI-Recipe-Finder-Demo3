---
title: "Event 3"
date: 2026-07-07
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# EVENT REPORT "CLOUD ARCHITECT FINALS" 

### Event Objectives 

-   Organize the final round of the Cloud Architect tournament, creating a practical playground for students to test their real-world knowledge of AWS infrastructure design and operations. 
-   Provide in-depth technical sharing sessions (Tech Sharing) from engineers and experts surrounding the AWS Cloud Practitioner certification, security automation with AI (DevSecOps), and system risk management (Monitoring & SLA). 

### List of Speakers 

-   **Thinh Nguyen** - DevOps/DevSecOps/Cloud Engineer, Styl Solutions 
-   **Ngo Le Tan Huy** - Presenter on AWS Cloud Practitioner Roadmap 
-   **Nguyen Huynh Son** - Freshly graduated from HUFLIT / Member of AWS Student Builder Group / Ex-Infrastructure Reliability Engineer at SPS 

### Key Highlights 

#### Dramatic Cloud Architect Finals:
The match took place between the KLKAT and Ngu Dai Hiep teams. The beginning saw an extremely close neck-and-neck score race. A uniquely unprecedented event in the tournament's history occurred when both teams fell into negative scores midway. Towards the end, due to a bold move by Ngu Dai Hiep choosing the "Star of Hope" and answering incorrectly, their negative score plunged even deeper. As a result, KLKAT won the championship without needing to answer the final question, becoming the first team in history to win with a negative score. 

#### Automated Pentesting with AWS Security Agent:
Speaker Thinh Nguyen from Styl Solutions brought a fresh perspective on DevSecOps.
- Highlighted the bottlenecks of traditional pentesting: Time-consuming, expensive ($5k - $20k), and heavily reliant on the pentester's skill level.
- Introduced the "Frontier Agent" running on the Amazon Bedrock platform. This is an autonomous agent capable of reading architecture documents (Markdown/Terraform), automatically reviewing code to find security vulnerabilities, and actively scanning and self-attacking (Pentesting) running systems to verify bugs. Although priced around $50/Task-Hour, it is an extremely optimal choice compared to hiring a professional pentest team ($10,000). 

#### Strategy to Conquer the AWS Cloud Practitioner Certification (CLF-C02):
Speaker Ngo Le Tan Huy systematized the roadmap for preparing for AWS's foundational certification.
- The exam lasts 90 minutes (with an extra 30 minutes for non-native English speakers), structured into 4 domains: Cloud Concepts (24%), Security and Compliance (30%), Cloud Technology and Services (34%), and Billing/Pricing (12%).
- Shared practical exam tips: Study using "Keyword Thinking" to associate services with use cases (e.g., choosing SQS when seeing "Decouple"), build the habit of thoroughly analyzing incorrect answers during mock tests, and utilize elimination techniques (ruling out non-existent services). 



#### SLA & Monitoring - The Gap Between Infrastructure and User Experience:
Speaker Nguyen Huynh Son presented the true mindset of system monitoring.
- SLAs (Service Level Agreements) are crucial for setting expectations, service accountability, and risk management.
- Pointed out a classic misconception: "A healthy infrastructure (where all CPU and RAM metrics are good) does not equal a happy user experience". For example, even if EC2 or ALB runs stably, users still cannot log in if the DB connection fails.
- Shifting perspective through the Monitoring Pyramid: Instead of just looking from the bottom up (Infrastructure -> Application), engineers must monitor from the top down, measuring business metrics (such as successful login rates and order numbers) to genuinely capture user sentiment. 

### What I Learned 

- **DevSecOps Trends:** Witnessing the future of security where AI Agents (represented by Bedrock) can automate the entire security lifecycle (from design review to pentesting). However, one must also understand the limitations of AI Agents, such as failing to bypass MFA/Biometrics or struggling to detect complex business logic flaws.

- **Certification Mindset & Practice:** A certification is not just a piece of paper, but a logical thinking process built on the AWS Framework. Rote memorization should be avoided in favor of direct practice on the AWS Free Tier and deep analysis of question choices. 
 
- **"Plan for Failure" Mindset:** Echoing Dr. Werner Vogels' quote, "Everything fails all the time," engineers must build monitoring systems centered around user behavior (Customer Journey) rather than fixating solely on hardware metrics. 

### Experience at the Event 

- **Networking and Learning:** Watching the live Cloud Architect finals was extremely thrilling and offered valuable lessons on tactical gameplay and staying calm under pressure. 
- **Practical Insights:** The speakers were talented young professionals with deep practical experience, helping me better understand the gap between configuring a system "just to make it run" versus building a system that is secure, cost-optimized, and focused on user experience. 

#### Event Photos: 

![Event 3](/images/4-Event/Event3_1.jpg)
![Event 3](/images/4-Event/Event3_2.jpg)