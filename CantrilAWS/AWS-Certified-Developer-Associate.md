# AWS Certified Developer Associate Course

---
title: "Aggregate notes on Cantril's AWS Certified Developer - Associate Course"  
date: 2024-02-11  
tags:
- Career
- Course
- Certification
- AWS
---

MD Links: [[associate-course-bundle]], [[courses-breakdown]]

Relevent Websites: [Certified Developer Course](https://learn.cantrill.io/courses/enrolled/1101194)

## Introduction & Scenario

### [Public Introduction](https://learn.cantrill.io/courses/1101194/lectures/30553576)
- There is a signifigant ammount of overlap with Sollutions Architect Associate (<- Add Link) about 60%
- Course Topics
    - This course will start with networking, encryption, and the JSON and Yaml file formats
    - Move onto AWS Fundamentals
    - Core AWS Topics (Overlaps with Sollutions Architect) <- This is a large ammount of content
    - Developer Cert Specific Topics

### [Finding and Using the Course](https://learn.cantrill.io/courses/1101194/lectures/24663362)
- [Course Github Repo](https://github.com/acantril/aws-dev-associate)

### [Site tools and features](https://learn.cantrill.io/courses/1101194/lectures/39441493)
- There is an available slack learning community, though I am not intrested in it at the moment
- [Labs Link](https://github.com/acantril/learn-cantrill-io-labs) repo that contains fully featured projects and a number of other demos

### [AWS Exams](https://learn.cantrill.io/courses/1101194/lectures/24663371)
- Cantril believes that starting at the associate level is the correct choice regardless of AWS's suggestion of starting at the foundational level
- Roll based certification are specific to a certain roll that is widespread within large organizations
    - Foundational, Associate, and Professional certs all fall within this Roll based categorey
- The other category of certification is Specialty
    - These contain a 50/50 split between a specialty skill and AWS skills
    - The level of AWS skills required is somewhere between Associate and Professional level depending on the certification
- Cantril recommends starting with the Sollutions Architect Associate (SAA) (<- Add Link) Certification
    - After finishing this section of the Certified Developer Associate Course I will be switching over to the Sollutions Architect Associate Course
    - This recommendation stems from his oppinion that the SAA Cert is the easiest of the Associate level courses, and that it is foundational for all other courses 
    - Cantril's Route: SAA -> CDA -> SOAA -> MUCH HARDER -> SAP -> DOEP -> Maybe CP -> Any Specialty Cert

### [Course Scenario - Animals4life](https://learn.cantrill.io/courses/1101194/lectures/24663376)
- This is the ficticious buisness that we will be using throughout the course
- Animals4life
    - Animal Rescue and Awareness Organization
    - Global, with HQ in Brisbane Austrailia - 100 Staff
    - .. Call center, Admin, IT, Marketing, Legal & Accounts
    - ~100 REmote workers across Australia and glbally
    - .. Animal care, activists & Lobbyists
    - Major offices in London, New York & Seattle
- Animals4life Infrustructure
    - Small on-premises datacenter in Brisbane
    - Encouraged to move out of datacenter
    - Badly Implemented AWS trial in SYD Region
    - A few isolated Azure/GCP Pilots
    - Global Offices & mobile staff utilize Brisbane Infrastructure
    - Const-conscious but progressive management team
- Current Problems
    - Legacy on-premises hardware is **failing**
    - AWS/Azure Pilots are **messy** and **not best practice**
    - **Performance isssues** for field workers
    - **Lack of High Availability and Scalability** - hardware is expensive
    - Staff skills/capabilities struggle .. **little automation**
    - Global expansion concerns - **cost for new infrastructure**
- Ideal Outcomes
    - Fast performance for all field workers
    - Able to deploy into **new regions quickly** when required
    - **Low cost** & **scalable** base infrastructure
    - **Agility** - spin up new marketing campaigns, social and progresive applications (**IOT**, **Big Data**, etc)
    - **Automation** - low base staffing costs
- [Animals4life Scenario PDF](https://github.com/acantril/aws-sa-associate-saac02/blob/master/01-Introduction/01_CourseScenario/Animals4Life%20Scenario.pdf)
