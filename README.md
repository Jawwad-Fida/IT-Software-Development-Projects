# IT Software Engineering Projects

## Projects overseen as an IT Project Manager (Specialist, Enterprise and OTT Solutions) at [Robi Axiata Limited](https://www.robi.com.bd/en)

### [Binge - Online video streaming OTT platform (binge.buzz)](https://binge.buzz/) - 📘 Robi's OTT Platform
Binge is an online video streaming OTT (Over-the-top) platform that offers endless entertainment in the form of Live TV, web series, films, dramas, movies, Video-On-Demand to Binge Exclusive Originals and much more. Binge provides a truly seamless entertainment experience to customers where they can watch as much as they want, whenever they want, without a single commercial. Binge is Robi's owned streaming platform.  It is currently available 100+ countries all over the world. Binge is currently available in IOS, Android, Large Screen, Web.
Content Language: English, Bangla.

**Some Notable Achivements**: 
* On Net Free & Off net premium (Android and IOS): On Net customers (Robi Telecom customers) will be able to watch all content without purchasing any SVOD pack. All Off Net customers (other telecom customers) will have to purchase subscriptions to watch premium content. All free content will be available to both On Net & Off net customers as per usual.
* CDN migration: Initiated CDN migration of Binge offnet users traffic from Nexdecade CDN servers (third-party) to Robi own internal CDN servers. This migration will result in annual savings of 80Mn BDT for Robi as the company reduces reliance on third party.
* Technical project management and cross-platform integration during the complete in-house overhaul of company's OTT platform (binge.buzz), which resulted in significant cost savings of 112.32 mBDT (1.14 mUSD) per year by streamlining operations and consolidating services under one internal DevOps team, thereby reducing the complexity of Binge ecosystem.
* Solving the abnormal otp related SMS issues (2.2 million SMS) and TPS limit exceeded complaints faced by Binge due to growing number of subscriptions by: Ensuring DDOS protection shield is active at application layer to block brute force attacks by hackers, and Ensuring proper blocking mechanisms are in place to block numbers that are generating multiple SMS (i.e., implementing blocking mechanism for a MSISDN to simultaneous 10 requests in a min)
* Contributed to IT Simplification Project (Robi CIO action item) to save costs by itentifying VM/hardware resources that can be offloaded. As Robi was facing resource crunch in its data center, to help in this resource crunch problem, I found out which Binge VM resources utilization was low for the last one year and can be offloaded. Hence, some VMs were offloaded freeing up around 2.22 TB space. This contributed BDT 6 mBDT (54,546 mUSD) per year savings to IT Simplification Project from my end.

<img width="50%" alt="Home page 1" src="https://github.com/Jawwad-Fida/IT-Software-Development-Projects/assets/121283896/c132b60b-fdcb-4c02-8ea7-15c61d8a22c8">
<img width="50%" alt="Binge Watch TV" src="https://github.com/Jawwad-Fida/IT-Software-Development-Projects/assets/121283896/b4a64596-2103-4ed1-a3c9-ac5911dc67eb">
<img width="50%" alt="Binge user details page" src="https://github.com/Jawwad-Fida/IT-Software-Development-Projects/assets/121283896/ae719044-efcd-4258-a1ed-2d90f5f6b45f">


### [Customer Feedback Management (CFM)](https://cfm.robi.com.bd/) - 📘 Robi's central feedback management solution
CFM is a self-sustained, real-time, human independent feedback management system that automates the collection and management of customer feedback from different customer service channels into daily business operations. 
CFM solution will enable Robi to manage customer feedback centrally from a single platform, automate the collection and management of customer feedback from different customer service channels and helps to channelize the feedback directly to the relevant functions for close looping. CFM solution is integrated with the customer interacting solutions and is designed to collect customers feedback, analyze feedback based on different criteria and act depending on customer feedback with the goal to optimize the customer experience. CFM solution also includes intuitive dashboard along with reporting that will provide clear visibility of the whole Robi and Airtel customers on their level of satisfaction and areas to improve.

**Main task:** Project Management, guided the team and completed the development, integration, service and infrastructure UAT & Information Security (IS) check for CFM in 2 phases:
* Phase 1: Developed and deployed CFM Solution as per scope on July 20, 2023
* Phase 2: New development scope has been identified during phase 1 and deployed the features as complementary on December 06, 2023

The channels that are integrated with CFM solution are Contact Center, Single App (Robi & Airtel), USSD, 121 IVR, Retailer IVR, Email (Int’l Roaming), Messenger Chatbot, Whatsapp chatbot, Corporate Website, Web Selfcare etc. There are few more channels that will be integrated based on new channel partner onboarding and their readiness. CFM is ready to integrate new channels with both capability - API connectivity & File sharing.

Notable Key Features and Benefits: 
* Dynamic management portal for survey creation, survey mapping and distribution.
* Support for both SMS and Web-based surveys (Both Bangla and English language support)
* Feature for Schedule Survey, Instant Survey & automated survey after customer interaction.
* Multi-layered/branching survey creation (Channel wise, brand wise, Interaction wise, USSD node wise, IVR menu wise etc.)
* Channel wise broadcast logic (Max Surveys Per Day, N'th Interaction survey)
* Sentiment Analysis based on customer’s feedback.
* Close Feedback Loop, SLA management, Alert generation on SLA violation
* Dynamic dashboard to display day to day survey statistics, and Dynamic Reporting portal to analyze customer data and create extensive reports.
* API based and file based integration with multiple channels.

<img width="50%" alt="CFM - Max counter and Nth interaction" src="https://github.com/Jawwad-Fida/IT-Software-Development-Projects/assets/121283896/d8c63bf0-d0a3-4a31-8f3f-9ad1a69d6bbb">
<img width="50%" alt="CFM - Multiple survey fire" src="https://github.com/Jawwad-Fida/IT-Software-Development-Projects/assets/121283896/93cadfdd-a7c5-42ba-803f-c9acec000787">
<img width="50%" alt="CFM broadcast logic" src="https://github.com/Jawwad-Fida/IT-Software-Development-Projects/assets/121283896/356ac867-c550-4d58-984c-d1c6a1bee289">
<img width="50%" alt="CFM - Telephonic Survey" src="https://github.com/Jawwad-Fida/IT-Software-Development-Projects/assets/121283896/630c9a13-f835-40ce-88b7-e022e34bd9e7">


### [Orchestrator RPA](https:#) - 📘 Centralized platform to monitor and control Robi's RPA (Robotic Process Automation) bots
Robi Axiata Limited several RPAs in place with a variety of functions in various departments. When these RPA servers go down, the entire workflow becomes stalled, which can only be rectified by manually restarting the RPA via the command prompt. Hence, without the trouble of command prompt, a centralized hub with numerous functionalities such as enable, disable, start, off, schedule, multi-scheduling of these RPA was required to handle this issue. As a result, a centralized system called Orchestrator RPA can be incorporated to manage and monitor all RPA processes in the organization. This is a web application that manages the execution of recurring tasks. This online interactive digitized solution Orchestrator RPA will  erase all obscures and enhance to rectify in an user friendly manner.  Overall, It is a single control room where users can plan and run bots on desktop and virtual machines, create sequences, monitor bot status, and analyze the results of their work. 

Key Features:
* Role based User Access Management.
* RPA (Robotic Process Automation) Onboarding.
* Log report of each RPA.
* Scheduling (One-time schedule, Multi-schedule, Enable/Disable).
* Real-time Notification.

Key Deliverables: 
* Role based User Access Management.
* RPA (Robotic Process Automation) Onboarding.
* Log report of each RPA.
* Scheduling (One-time schedule, Multi-schedule, Enable/Disable).
* Real-time Notification.
* ELK Integration.

Key Benefits:
* In-house built; Using a third-party orchestrator can be very expensive.
* All RPA logs can be seen from this solution; No need to login into ELK for log analysis.
* Perfect solution for low-level automation in comparison with the market applications.

**A Notable Achivement**: 
* Contributed to IT Simplification Project (Robi CIO action item) to save costs by itentifying VM/hardware resources that can be offloaded. There were multiple RPAs no longer being used by Business team. Hence, the RPAs were offloaded and the server was decommissioned as it was no longer required. Also, scheduling time of RPAs was assessed, and the RPAs that had no conflict in scheduling time were brought together into a single server, thus reducing more resources. Total space freed up is 850 GB. 

### [VAS CP Portal (Content Provider Onboarding)](https://vascp.robi.com.bd/login) - 📘 Digitize e2e VAS concept lifecycle
VASCP is a web application will bring operational excellence for VAS new partnership / service / campaign onboarding & will help to add potential revenue stream by executing faster partnership which will bring potential revenue contribution to VAS. This portal will empower e2e VAS digitization of any new service onboarding for Robi MO VAS & New Business department & will ensure vendor / partner / Content Provider i.e VAS CP Lifecycle in a digitized way.    

Key Deliverables: 
* Portal development for new business concept submission by partner & do all relevant activities by Robi Concern to make product Go-Live following all steps including keep tracking of required approvals in full e2e digitized way
*  Individual Portal for Partner, Robi VAS & New Business department & other relevant execution unit to monitor each activity & ensure proper SLA
* Effective Dashboard for Visualization & Monitoring with all ongoing project status 
* Report download options to check historical data.
* Auto Email generation as instant task notification. 
* Concept submission
* Concept's related GM can assign Project manager. Project manager can assign other department's SPOC according to his/her need.
* PM can configure stage for each concept. Example:
 * Binge Content: Artist Director Involment
 * Binge Content: Binge Show
 * Binge Content: Final Script
 * Binge Content: Launch
 * Binge Content: Post Production Meeting, etc.


### [info360 and Robi e-learning platform](https:#) - 📘 Robi Call Center and Walk in center agents lifecycle management

**Info360**: Info360 is information/knowledge sharing portal for Robi which contains all products details, offers and campaigns information which required to serve customer query for both brands (Robi + Airtel). It is one of the basic hygiene factors for customer service, without which customer service will be seriously impacted as well as customer experience will be hampered.

**e-learning**: The main objective of e-learning portal is to have a training portal for agents of both brands where they can attend training and exam to ensure proper readiness to serve customer.



