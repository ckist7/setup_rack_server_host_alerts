Technical Project Proposal
This repository contains the required materials for submitting a project proposal for upper-level Computer Technology courses and Capstone projects

Chris Kist
CPT 298-01
January 28, 2026
Set Up Rack Server Host Alerts
1.	Project Identification
•	Project Title: Set Up Rack Server Host Alerts from Grafana to the Discord Server
•	Course: CPT 298-01 Capstone
•	Term: 2025-2026 Spring Semester
•	Student Name: Chris Kist, Shayla M, Aaron
•	Primary Contact: Christian.kist@mainecc.edu
•	Proposed Start Date: 2/5/2026
•	Proposed End Date: 3/8/2026
2.	Project Selection & Motivation 
•	This project will give us a chance to step into unfamiliar territory and get hands on with learning new things. 
•	We chose this project to help the future classes and help ourselves learn more about the Computer Technology world. 
3.	Problem Statement
•	Right now, there is no alert system set up for the Discord server that is easy to monitor. 
•	The students and professors are affected by this, if it is not properly alerted, then it cannot be taken care of in a timely manner.  
4.	Proposed Solution Overview
•	We will set up a Rack Server Host from Grafana and link it to the discord server.
We will set the server up with metrics collectors (Prometheus/ Node Exporter), Grafana, set Alert Rules (CPU, RAM, Disk) and have webhook for a contact point.  
5.	Technical Stack & Tools
•	Operating System(s): Ubuntu (most work will be done on VM)
•	Programming Language: Ruby for the Rack Server, Golang for Grafana, Python3 
•	Frameworks/Libraries: Grafana, Prometheus, Node Exporter, Query and Rule Language, Webhook, Notification/Integration Layer
•	Databases/Storage: Prometheus Time-Series Database
•	Infrastructure: The core infrastructure component is the Rack Server
•	Tools: Ubuntu OS, Grafana, Rack Server, UV Desk, Prometheus, Node Exporter, Discord Webhooks, PromQL, Linux Command Line
6.	Prerequisite Knowledge & Skills
•	I do not believe we have skills in the tools used except for using Ubuntu, and command lines in other classes. So we will be gaining more knowledge than applying existing knowledge. 
7.	Project Scope & Deliverables
•	The MVP for this is the final document. It is going to be easy to read and comprehend. Have all the required information without any noise as well 
8.	Milestones & Timelines
•	Phase 1: Research & Design Week 1; Create outline of steps needed. 
•	Phase 2: Core Implementation Week 2; Go through the steps of Phase 1 to create the Rack Server. 
•	Phase 3: Testing & Refinement Week 3; Go through extensive testing to ensure that our alerts are properly working. 
•	Phase 4: Documentation & Presentation Week 4; Type up the steps and actions done to complete the project and work with the team members to prepare the presentation. 
9.	Risks, Constraints & Dependencies
•	Technical Risks: The fact we do not have much combined experience with completing a project like this. 
•	Time Constraints: Time could become an issue if we do not figure out the proper way to complete the project. 
•	External Dependencies: VM access, GitHub, Discord, websites on creating webhooks and rack servers. 
•	Mitigation Strategy: We can search and post things that we find to our group chat and talk about what we think we can use and what we cannot. 
10.	 Security, Ethics & Safety Considerations
•	Grafana access will be needed 
•	Prometheus and Node Exporter are bound to localhost or internal interfaces only. 
•	Discord webhook URLs are treated as secret
•	Responsible monitoring, transparency and appropriate alerting
•	System Stability and Failure Handling
11.	Purpose
•	Evaluating project fit and scope
•	Assess technical readiness
•	Approve or redirect project direction before implementation

12.	Team Structure
•	We will work as one unit, using the group chat to share information and where we are with the project. 
13.	Documentation & Knowledge Transfer 
•	Will use README 
•	A repository on my GitHub
14.	Faculty/ cpt. Internal Resources Requested
•	VM Access
•	Grafana 
•	Discord Webhook access
•	Prometheus/Node Exporter
15.	Instructions:
•	Fork this repository – please name it what you intend on naming your final project as this will be your project repository. You can make this private if you’d like, but you’ll need to invite at least myself to it.
•	Complete the ‘proposal.md’ file
•	Commit all changes with clear commit messages.
•	Submit the repository URL via Brightspace if part of an assignment, or send it to me via email or discord message if you are undertaking this for extra credit.
•	Do not get started on this project until your proposal has been approved
16.	Acknowledgement of Expectations 
•	This is a self-directed technical project
•	I am responsible for research and troubleshooting
•	Evaluation will consider process, documentation and professionalism
17.	This proposal is considered a living document until approval. Once approved, scope changes require instructor review while this readme SHOULD be updated your proposal will live with your final repository in perpetuity.

Signature (Name & Date): 

Student 1:____________________________ Date: 2/9/2026

Student 2:____________________________ Date: 2/9/2026

Student 3:____________________________ Date: 2/9/2026

Professor:____________________________Date:2/9/2026

