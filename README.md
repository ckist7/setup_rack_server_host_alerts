
Chris Kist
CPT 298-01
January 28, 2026
Set Up Rack Server Host Alerts
    1. Project Identification
    • Project Title: Set Up Rack Server Host Alerts from Grafana to the Discord Server
    • Course: CPT 298-01 Capstone
    • Term: 2025-2026 Spring Semester
    • Student Name: Chris Kist, Shayla Manson, Colby Smith
    • Primary Contact: Christian.kist@mainecc.edu
    • Proposed Start Date: 2/5/2026
    • Proposed End Date: 3/8/2026
    2. Project Selection & Motivation 
    • This project will give us a chance to step into unfamiliar territory and get hands on with learning new things. 
    • We chose this project to help the future classes and help ourselves learn more about the Computer Technology world. 
    3. Problem Statement
    • Right now, there is no alert system set up for the Discord server that is easy to monitor. 
    • The students and professors are affected by this, if it is not properly alerted, then it cannot be taken care of in a timely manner.  
    4. Proposed Solution Overview
    • We will set up a Rack Server Host from Grafana and link it to the discord server.
We will set the server up with metrics collectors (Prometheus/ Node Exporter), Grafana, set Alert Rules (CPU, RAM, Disk) and have webhook for a contact point.  

	-- Brett Note --
		Grafana is already installed!  I'll provide you with a webhook to the Discord server and you'll just be responsible for utilizing Grafana's internal "alert" mechanism for sending the alerts to Discord!
	-- End Brett Note --
	
    5. Technical Stack & Tools
    • Operating System(s): N/A
    • Programming Language: N/A
    • Frameworks/Libraries: Grafana,Query and Rule Language, Webhook, Notification/Integration Layer (Alerts)
    • Databases/Storage: N/A
    • Infrastructure: N/A
    • Tools: Grafana, Discord Webhooks, PromQL

	-- Brett Note --
		Grafana is already installed!  You won't need to use many of these as the technology is already running!
	-- End Brett Note --
    6. Prerequisite Knowledge & Skills
    • I do not believe we have skills in the tools used except for using Ubuntu, and command lines in other classes. So we will be gaining more knowledge than applying existing knowledge. 
	-- Brett Note --
		I'd research Grafana and specifically the "Alerts"!
	-- End Brett Note --
	
    7. Project Scope & Deliverables
    • The MVP for this is the final document. It is going to be easy to read and comprehend. Have all the required information without any noise as well 
    8. Milestones & Timelines
    • Phase 1: Research & Design Week 1; Research Grafana and create outline of steps needed
    • Phase 2: Core Implementation Week 2; Begin building alerts
    • Phase 3: Testing & Refinement Week 3; Go through extensive testing to ensure that our alerts are properly working. 
    • Phase 4: Documentation & Presentation Week 4; Type up the steps and actions done to complete the project and work with the team members to prepare the presentation. 
	
	-- Brett Note --
		Please take note of my edits to this section above!
	-- End Brett Note --
	
    9. Risks, Constraints & Dependencies
    • Technical Risks: The fact we do not have much combined experience with completing a project like this. -- Brett note: This is a LOT simpler than your outline!  Please review the Grafana documentation, specifically the alerts section!
    • Time Constraints: Time could become an issue if we do not figure out the proper way to complete the project. 
    • External Dependencies: VM access, GitHub, Discord, websites on creating webhooks and rack servers. -- Brett note: You don't need most of these!
    • Mitigation Strategy: We can search and post things that we find to our group chat and talk about what we think we can use and what we cannot. -- Brett note: Ask questions when you need help!
    10.  Security, Ethics & Safety Considerations
    • Grafana access will be needed 
    • Prometheus and Node Exporter are bound to localhost or internal interfaces only. -- Brett note: Already hooked up! Don't worry about this
    • Discord webhook URLs are treated as secret -- Brett note: I will add this to Grafana for you!
    • Responsible monitoring, transparency and appropriate alerting
    • System Stability and Failure Handling

    11. Team Structure
    • We will work as one unit, using the group chat to share information and where we are with the project. 
    12. Documentation & Knowledge Transfer 
    • Will use README 
    • A repository on my GitHub
    13. Faculty/ cpt. Internal Resources Requested
    • VM Access
    • Grafana 
    • Discord Webhook access
    • Prometheus/Node Exporter-- Brett note: These are already setup!
    14. Acknowledgement of Expectations 
    • This is a self-directed technical project
    • I am responsible for research and troubleshooting
    • Evaluation will consider process, documentation and professionalism

Signature (Name & Date): 

Student 1:____________________________ Date: 2/6/2026
		
Student 2:____________________________ Date: 2/6/2026

Student 3:____________________________ Date: 2/6/2026
