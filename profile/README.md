![Original on Transparent](https://github.com/unstructai/.github/assets/5151108/981823ad-4137-450f-9f8b-530f7fd225bf)<br><br>


# An AI-Integrated Open-Source Alternative to PagerDuty

## How much are you paying for Incident Management? 🤔

- **Paging/On Call**: ($$)
- **SIRT/Incident Management**: ($$)
- **Analysis/Postmortem**: ($$)
- **SLO/SLI Management**: ($$)
- **DFIR (Digital Forensics & Incident Response)**: ($$)
- **Status Pages**: ($$)
- **Uptime Monitoring**: ($$)

...And the list/madness continues. 

At [UnStruct.ai](https://github.com/unstructai), we're on a mission to cut through this nonsense.

In just a few minutes, you can deploy a solution that integrates world-class open-source projects like [Dispatch by Netflix](https://github.com/Netflix/dispatch/), [Timesketch by Google](https://github.com/google/timesketch), [GoAlert by Target](https://github.com/target/goalert), and [Uptime Kuma by Louislam](https://github.com/louislam/uptime-kuma). We've enriched these with AI, added our personal touch, and made significant enhancements. Setting it up is a breeze (with just one command), and for those curious about the internals, feel free to dive into the 500,000+ lines of code that tie everything together.

👉 https://github.com/unstructai/.github/blob/main/unstruct-install.md

## One more thing: 💡

> **Did You Know?**  
> The average downtime cost for medium to large companies stands at a staggering **$10,719/min**. Furthermore, a single cybersecurity incident can set you back by **$4.35 million**. UnStruct's proposition? **Slash these costs by over 15%**.


<br><br>
# UnStruct.AI Components

With UnStruct.AI, you're not just getting another cybersecurity tool – you're getting an all-in-one powerhouse. Instead of juggling multiple tools and racking up costs for each, get everything under one roof. Whether it's for paging, incident response, analysis, status updates, SLO/uptime monitoring, or a sprinkle of tech magic – we've got you covered. And the best part? **It's all free**.

## 🤖 **Incident-Copilot**  
   *Orchestrating Incident Response*  
   - **OpsGPT Bot**: Engage with your dedicated incident copilot and revolutionize your incident response experience.
   - **Dynamic Case Management**: Anticipate and address issues even before they escalate into incidents. Maintain a proactive stance.
   - **Signal Processing**: Efficiently detect, interpret, and respond to critical production signals from varied sources, ensuring you're always acting on relevant information and not getting bogged down by distractions.
   - **Adaptable Plugin-Based Architecture for Scalable Integrations**: In Unstruct, plugins serve as the essential integration glue, seamlessly connecting the platform to a variety of widely-used external systems across the industry. These include, but are not limited to, Slack, Jira, PagerDuty, ServiceNow, Zoom, Sentry, and Google, among others


## 🔍 **StoryCurve**  
   *Collaborative Incident & Forensic Analysis*  
   Dive deep into insights, stories, and forensic analysis. Get a granular understanding of every incident with collaborative tools.

## 📢 **Uptime-Umbrella**  
   *User-Centric Status Pages & More*  
   Modern status updates, user feedback, incident mapping, and automated page updates. Plus, never miss a beat with SLO & Uptime Monitoring!

## 🚨 **Peace-Pager**  
   *Reliable On-call & Alert Management*  
   Ensure swift responses with on-call scheduling. Benefit from seamless Slack integration and robust API access.

---

Try UnStruct.AI today and embrace the future of cybersecurity incident response.


<br><br>
# Installation

Setting up comprehensive software can often become a tedious and error-prone process, especially when it involves integrating multiple components, each with its distinct configurations and settings. At UnStruct.AI, we understand this challenge. That's why we've simplified the installation process, ensuring you spend less time setting up and more time benefiting from our platform's capabilities.

## One Command Install

Whether you're setting up for the first time or want to uninstall, we've distilled the process into one simple command:
```bash
./deploy_unstruct.sh install|uninstall|upgrade
```

Full instructions at https://github.com/unstructai/.github/blob/main/unstruct-install.md

## Want a Cloud Solution?
Interested in a hassle-free, cloud solution without dealing with installation and maintenance? Contact us at unsales@unstructai.com. For the first 10 customers, we will only charge you (GCP) hosting fees for the first year of your usage.  

<br><br>
# Main Features

- **Plugin-Based Architecture with 20+ Integrations:** Including Slack, PagerDuty, Jira, Google, Github, Zoom, Sentry, UnStruct Statuspage, and more.
  
- **Incident Custom Checklists:** Streamline your process with SLA tracking, reminders, and easy configuration.
  
- **Custom Incident Fields:** Tailor the platform to meet the unique attributes of your incidents.
  
- **Natural Language Parsing:** Experience AI-assisted task assignment options, currently in Beta.
  
- **One-Click Task Creation/Update:** Manage tasks with unparalleled simplicity and efficiency.
  
- **Automated Comms Reports:** Receive executive and tactical reports generated by advanced AI, currently in Beta.
  
- **Automated Postmortem Checklists:** Benefit from inclusive AI-generated insights and stories, currently in Beta.
  
- **Zoom Transcript Processing:** Experience auto-summation and intelligent task suggestion functionalities.
  
- **Best Practices Enforcement:** Built right into the platform; it’s training and education with the highest ROI.
  
- **TTP Monitoring:** Rely on automated monitoring of Slack, Zoom, and document data for tactics, techniques, and procedures.
  
- **Dynamic Search and Engagement Filters:** Enhance engagement with customizable filters for individuals, teams, services, runbooks, and more.
  
- **Dynamic Signal Processing:** Navigate through the noise and manage pager storms effectively. Automatically transfer all the context as the issue escalates.
  
- **Probable Causes & Signal Aggregation:** Seamlessly integrate with platforms like Sentry, Uptycs, Google, PagerDuty, and more. Currently in Beta.
  
- **Automated Annotations, Attribute Mining & Timelines:** Foster comprehensive and collaborative incident management.
  
- **Modern, User-Centric Status Pages:** Enjoy automated updates, user feedback, and incident mapping with specific pages.
  
- **SLO & Uptime Monitoring:** Utilize multiple monitor types, API integration, and ready-to-use SLO monitoring.
  
- **Streamlined On-Call Handoff:** Experience formal handoffs, reminders, and contextual summaries.
  
- **New Analytics Dashboards:** Focus on people, feedback, and more.
  
- **Über Timeline:** Access org-wide aggregation of key metrics and attributes, such as sentiment.
  
- **UI Enhancements:** Navigate with ease through our modernized and user-friendly interface.
  
- **Tag-Based Auto Participant Pulling:** Leverage tags and metadata for participant compilation, currently in Beta.
  
- **Best Practices & Queries Extraction:** Extract valuable insights directly from metadata.
  
- **API Keys & OIDC OAuth, RBAC and Private Incidents:** Integrate securely and easily.
  
- **OpsGPT Incident Copilot:** Get answers to up to 30 types of incident-related questions from our OpsGPT Bot, currently in Beta.
  
- **Cybersecurity Forensic Analysis:** Employ automated analyzers, sigma rule creation, threat intelligence, and streamlined investigation with built-in search templates.
  
- **Automated Toil Tracking System:** Systematically record, analyze, and manage work toil.
  
- **And Many More:** Explore additional features including on-call scheduling, escalations, rotations, and more.


<br><br>
# Visual Preview & In-Depth Feature Insights
<br>

## Dynamic Incident Engagement & Intelligent Search Filters
Navigating through the labyrinth of data during an incident can be a daunting task, requiring precision and efficiency. That's where UnStruct.AI’s Search Filters & Engagements feature steps in, serving as your compass in times of chaos. This powerful tool enables you to swiftly identify and engage the right individuals, teams, or service owners, ensuring that they are seamlessly looped into the incident's developments.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/58954d31-26fb-4501-8375-3c5f9e59065b)


<br><br>
## Addressing Pager/Alert Storms Effectively with Intelligence
No matter the size or type of your team, a common challenge faced by organizations in production is dealing with pager storms. This scenario, depending on your setup for alerting and monitoring, is a widespread issue that often results in over-monitoring and alert fatigue. More critically, making sense of these alerts can be daunting, hindering teams from identifying the root cause of issues.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/c68d6ab1-b0a3-4395-a75f-b258ecbc9081)
![image](https://github.com/unstructai/.github/assets/5151108/e881b8be-f41b-44a1-9712-8998907c57f1)

<br><br>
## Adaptable Plugin-Based Architecture for Scalable Integrations
In Unstruct, plugins serve as the essential integration glue, seamlessly connecting the platform to a variety of widely-used external systems across the industry. These include, but are not limited to, Slack, Jira, PagerDuty, ServiceNow, Zoom, Sentry, and Google, among others. The elegance of this architecture lies in its plug-and-play nature. For instance, if you are utilizing a documents plugin to store your incident reports on Google, and another user prefers Confluence, the transition is as simple as modifying a setting. This adaptability is where the true power of the architecture is realized.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/2a496581-b98f-4116-a551-d3e8ff912adb)

<br><br>
## Pioneering Customizable Postmortem Checklists for Consistent Reporting
A recurring challenge observed in the compilation of postmortems is the considerable time often spent in assembling these reports. This issue, coupled with a lack of consistency and customization in the reporting templates—whether provided by external entities or internal to your organization—results in varied quality across postmortems. If visualized, the quality of these reports can be graphically represented as being scattered, highlighting a pressing need for uniformity and adaptability.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/e186bf0d-39b7-4800-9d37-f0e48efe8743)

<br><br>
## Pioneering Custom Incident Checklists for Enhanced Responsiveness
UnStruct introduces the pioneering concept of Custom Incident Checklists, a feature designed to enhance and standardize the incident response process. The premise is straightforward yet highly impactful—every incident type is accompanied by a unique checklist that outlines the steps or actions required for that specific incident. For instance, a security incident will have a distinct checklist compared to an availability incident.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/6387f2a2-cec8-4744-9534-708df44c5338)

<br><br>
## Integrated Solution for Uptime/SLO Monitoring, Status Pages, and AI-Assisted Updates
In a digital landscape teeming with rudimentary status pages, envision a unified tool that seamlessly integrates uptime monitoring, SLO calculations, automatic notifications, and generative AI-driven updates. Such an innovative solution significantly diminishes the cognitive load on incident responders while enhancing system efficiency and reliability.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/9d0b982a-3605-4a51-a684-bbd2bbb3c4f3)
![image](https://github.com/unstructai/.github/assets/5151108/507b18c2-f175-4e8f-b7fa-c39f5ac35cd6)


<br><br>
## Unparalleled Infinite Configurability
We recognize that in a company of significant size, each team and organization may have distinct requirements and settings. With this understanding, Unstruct has been meticulously architected to accommodate a diverse range of configurations. The platform allows for the creation of multiple organizations within an instance, with each organization having the capability to host multiple projects.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/97dcb7b8-0189-4c5a-9af9-a79ad0ce3b6e)
![image](https://github.com/unstructai/.github/assets/5151108/38df4a3a-aed2-4722-bcc9-9fa9e007380f)

<br><br>
## Lightweight Task Framework
Tasks and follow-ups play a critical role in incident management. Tasks are actions aimed at resolution, essential to complete before marking an incident as closed, while follow-ups address additional concerns after stabilizing the incident. At UnStruct, we offer a seamless, lightweight mechanism to manage these elements efficiently.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/b6a97322-d82b-4332-9330-621685685021)
<img width="786" alt="Screen Shot 2023-09-24 at 5 17 45 PM" src="https://github.com/unstructai/.github/assets/5151108/d1c10a25-8c78-4198-bb8e-b440e11ff473">

<br><br>
## Incorporated Security DNA
At the heart of UnStruct lies an intrinsic commitment to security, providing a plethora of options to monitor signals from various sources like Sentry, Uptycs, Pagerduty and more. The platform facilitates the seamless tying of signals by extracting entities and aligning them with Signal definitions, which subsequently map to cases. This enables the automatic engagement of the appropriate individuals and initiates end-to-end orchestration designed to monitor critical signals vital to your company’s security interests.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/24c49a57-d1e3-4651-afa1-ca2132a4f056)
![image](https://github.com/unstructai/.github/assets/5151108/0d8236a9-b43a-44fc-a2ea-35289525840c)
![image](https://github.com/unstructai/.github/assets/5151108/7d676df5-493b-4cb4-80d2-ee5f12505bd0)
![image](https://github.com/unstructai/.github/assets/5151108/ae610e9d-39dd-43e5-9024-98a16b65e958)

<br><br>
## People-First Platform
UnStruct is meticulously designed with a foundational philosophy of being a people-first, customer-centric platform. This design ethos ensures that users gain profound insights as they engage in incident management and resolution processes. Recognizing the pivotal role of individuals in addressing various incidents, our platform unveils unprecedented insights into aspects such as toil, stress, and sentiment, among others.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/eb6b2e27-ec05-4d48-90d9-e13c567071fd)
![image](https://github.com/unstructai/.github/assets/5151108/67a60bed-51ad-4c53-888a-4f6ac36c67f6)
![image](https://github.com/unstructai/.github/assets/5151108/0628c079-ce35-403d-91f9-59b99ff63ddd)

<br><br>
## Embedded Privacy & RBAC
Acknowledging the paramount importance of privacy and role-based access control (RBAC), especially when managing private or sensitive incidents, UnStruct has been conscientiously designed with these principles embedded from the ground up. This foundational approach introduces the concept of private incidents – a feature allowing incidents to be marked as private, ensuring access is exclusively granted to designated responders.<br><br>
![image](https://github.com/unstructai/.github/assets/5151108/2259a422-5a01-4417-8111-9c10aff0506b)
![image](https://github.com/unstructai/.github/assets/5151108/8f57ced7-f65d-4ab2-bf03-47c8d5e7c5ae)

<br><br>
## Pioneering Non-Linear Timelines and Incident/Knowledge Graphs
Traditional timelines, with their seemingly infinite scroll, often prove cumbersome both during and after an incident. We recognized this challenge and devised an innovative solution to address it. While still in Beta, our approach aims to present timelines more intuitively, resembling a double-linked list. This design facilitates a quicker path to insights, allowing users to follow along seamlessly and efficiently.
<img width="1126" alt="Screen Shot 2023-10-17 at 10 46 23 AM" src="https://github.com/unstructai/.github/assets/5151108/0075d5e2-1d18-4312-bf1d-3c0842395914">
<img width="1377" alt="Screen Shot 2023-10-17 at 10 54 56 AM" src="https://github.com/unstructai/.github/assets/5151108/04a799b0-7836-4e5b-a4a3-e182fde15a2a">



<br><br>
# How can you contribute to our mission?

**UnStruct.AI**: More than Just a Product 

UnStruct.AI is not just a product; it's a vision for the future of cybersecurity incident response. As an open-source project, our strength comes from the collective intelligence and contributions of the community. Furthermore, it's built upon the foundation of several world-class open-source projects, harnessing their power and capabilities to offer a comprehensive and forward-thinking solution. Here's how you can be a part of this transformative journey:


- **Try unStruct**: Whether you have a mac or a Linux Dev box or a cloud instance, give unStruct a try. We have made it really, really easy to do. It is also very secure as your data stays with you.

- **Code Contributions**: Whether you're fixing a bug, improving performance, or adding a new feature, your code helps enhance UnStruct.AI for everyone. Check out our `CONTRIBUTING.md` guide to get started.

- **Feedback and Suggestions**: Used UnStruct.AI and have ideas on how it can be improved? We're all ears. Share your user experiences, suggest new features, or point out areas of improvement.

- **Documentation**: Great software is only as good as its documentation. Help us make UnStruct.AI accessible to all by improving guides, tutorials, and API documentation.

- **Spread the Word**: The more people know about UnStruct.AI, the better. Write about us on your blog, share on social media, or present at tech meetups and conferences.

- **Engage with the Community**: Join our forums, chat channels, or monthly community calls. Share your expertise, collaborate with peers, and help newcomers find their way.

- **Bug Reports**: Encountered an issue? Report it! Providing detailed bug reports helps us ensure the platform remains robust and reliable.

- **Integration and Extensions**: Build integrations with other tools, design plugins, or develop extensions to increase UnStruct.AI's utility.

- **Beta Testing**: Participate in our beta releases, test new features, and provide crucial feedback to ensure smooth and stable releases.

Every contribution, no matter how small, plays a vital role in shaping the future of UnStruct.AI. We're excited to have you aboard and together, let's revolutionize cybersecurity incident response!


<br><br>
# Documentation 📖

At UnStruct.AI, we believe that comprehensive documentation is at the heart of a successful open-source project. Our documentation is designed to provide users, contributors, and developers with the knowledge they need to get the most out of UnStruct.AI.

## Getting Started 🚀
If you're new to UnStruct.AI, start here:
- **Installation Guide**: Step-by-step instructions on setting up UnStruct.AI.
- **Quick Start Guide**: Dive right in and see UnStruct.AI in action.
- **User Manual**: Comprehensive guide on all features and functionalities.

## For Developers 👩‍💻👨‍💻
For those looking to contribute or integrate with UnStruct.AI:
- **API Reference**: Detailed information about our API endpoints.
- **Development Guide**: Best practices and guidelines for contributing code.
- **Integration Tutorials**: Learn how to integrate other tools and services with UnStruct.AI.

## Advanced Topics 🧠
Dive deeper into specific functionalities:
- **Scaling and Performance**: Best practices for running UnStruct.AI at scale.
- **Security Measures**: Ensure your UnStruct.AI installation is secure.
- **Custom Extensions**: How to create and integrate custom plugins.

## Community and Support 🤝
- **Forums and Discussions**: Engage with the community, ask questions, and share your experiences.
- **FAQs**: Answers to commonly asked questions about UnStruct.AI.
- **Troubleshooting Guide**: Solutions to common issues and challenges.

We're continually improving and expanding our documentation. If you have feedback, suggestions, or would like to contribute to the docs, please let us know!

> "Good documentation is hard to write. But when done right, it makes software shine." - *Anonymous*


<br><br>
---

## Our Decision to Go Open Source 🌍

We've taken a deep dive into our decision-making process, reasoning, and philosophy behind going open source. It's a journey of passion, innovation, and commitment to the community. 

📜 **[Read our full story here (It's a 30-min read)](https://www.linkedin.com/pulse/unstructai-fostering-community-innovation-incident-through-jalleda)**

From our foundational beliefs to the intricacies of our project decisions, we lay it all out for our community. Because transparency isn't just a word for us; it's our way of life.

---
