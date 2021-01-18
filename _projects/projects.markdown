---
layout: page
permalink: /projects/
---

# Capstone Project List


Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Wednesday (26 August) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (28 August). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - Two projects

### [Develop a kernel extension for an Open Source File System]({{site.baseurl}}/projects/pdfs/NetApp-SOS-Pitt-Capstone-Abstract-Fall-2020.pdf)

[Presentation]({{site.baseurl}}/projects/pdfs/Pitt Capstone - Fall 2020 Abstract.pptx)

**Project Background**

Embedded and distributed systems focused projects are not commonly provided at a bachelor’s level Capstone project. Our goal is to provide an opportunity for aspiring embedded systems engineers to gain experience in this area utilizing an open source embedded file system as a base for developing a specific kernel extension.

Developers at NetApp have been optimizing and enhancing our embedded proprietary file system (WAFL – write anywhere file layout) for over 20 years. Because of the proprietary nature of the file system we will be using an open source equivalent for this project. Working in the C language, students will gain real-life experience developing for embedded, distributed systems.

**Project Summary**

In this project, students will work with the FUSE open source file system installed on Ubuntu Linux platform. The project team will work through the detailed steps below to implement a kernel extension that reports the file system space usage.

**Project Details**

Over the course of this Capstone project, students will accomplish the following high-level goals:
- Download and install FUSE on Linux.
- Work through a NetApp provided initial custom example to understand the basic architecture.
- Create a read/write file system as an underlying test bed and explore the properties of this system.
- Write the kernel extension (using the C programming language) to implement a user space reporting function.
- Execute automated tests during the writing of the kernel extension. Enhance the automated tests as necessary.
- Enhance the file system to store user space consumed data in an in-memory database.
- Update the in-memory database based on incoming fileops.
- Implement a space enforcement feature which prevents write fileops that exceed a defined usage limit.


### [A Procedurally-Generated API Client Library for Go]({{site.baseurl}}/projects/pdfs/NetApp-Pitt-Capstone-Abstract-Fall-2020.pdf)

**Project Background**

In application development, RESTful APIs are an increasingly popular method of exposing functionality to users. This popularity has led to an effort known as the OpenAPI Initiative, which has formed to standardize how REST APIs are described and documented.

Developers at NetApp have designed a RESTful API for our storage operating system known as ONTAP®. Our API specification follows the OpenAPI standards, which allows our customers and partners to more easily read, explore, test, and consume our API. This, in turn, makes it simple for anyone to develop applications and scripts that are built on ONTAP!

These aren’t the only benefits of adopting the OpenAPI standard—doing so also brings a large ecosystem of tools built around OpenAPI. For this Capstone project, NetApp is looking to leverage the code-generating tool known as Swagger-Codegen. This tool can take any API specification written according to the OpenAPI standard and procedurally generate code designed for any number of purposes and written in any number of different programming languages.

A previously implemented Capstone project to generate an API client library for Python resulted in an officially-released Python Client Library(PCL).

**Project Summary**

In this project, students will work with the Swagger-Codegen tool to generate an API client library for Go. This procedurally generated library will enable simple management of ONTAP with Go.

**Project Details**

Over the course of this Capstone project, students will utilize several programming language and concepts, including:
- Working with HTTP to interact with RESTful software applications.
- Writing in Java to extend the Swagger-Codegen tool to utilize the unique functionality of the ONTAP REST APIs.
- Implementing object-oriented coding principles to design abstract templates used for procedural code generation.
- Leveraging the strengths of the Go programming language and the functionality of the ONTAP API to create a new Go library to be used by NetApp customers and developers here at NetApp!

**Note: NDA and/or IP agreement will need to be signed for this project.**


### Intalere - ONLY 1 OF THE FOLLOWING

###[Modernize Hospital Discharge Data Submission Application]({{site.baseurl}}/projects/pdfs/Intalere Capstone Project_CheckNet_Aug2020.docx)

**Project Background**

In most states, hospitals are required to submit accurate and complete discharge data files to the state collection agency each calendar quarter. Managing the collection and submission of this quarterly data to federal and state agencies can be a difficult and time-consuming task. Hospitals need to maintain knowledge of and compliance with rapidly changing rules, as well as have staff with the required technical expertise to manage the process.

CheckNet is utilized by hospitals, ambulatory surgery centers, as well as state data agencies and hospital associations to reduce errors and streamline the collection of discharge data. Easily adapted to the different needs and requirements of any state data agency, the CheckNet solution allows for direct submission of discharge data files via the internet. However, due to the building of this feature from vendors that provide applications for healthcare providers to aggregate claim data, there has been a decline in open market opportunities for CheckNet.

**Project Summary**

Students will develop a modern containerized CheckNet application moving the application into the cloud-hosted by Microsoft Azure and will identify any additional features that would help improve open market opportunities for the application. The front-end of this application is a web UI composed of independent UI microservices.

Students will also receive training and develop in a Domain Driven Design which is a methodology where developers work with the domain expert to visually create a model of the business domain. The business domain is the term used to communicate about concepts in the domain and all of the business rules in the domain. Students will gather information for the domain and graphical models from the domain expert and model it together. This graphical representation of the business domain helps everyone quickly understand the business domain, how things relate to one another, and drives the design of the software.

**Project Details**

Throughout this Capstone project, students will accomplish the following high-level goals:
- Complete Domain-Driven Design Training provided by Intalere
- Develop the project in an Agile development methodology  
- Gain real-world experience participating in a collaborative, product-engineering environment
- Research and engage with container technologies, including Docker and Kubernetes as well as work with additional technologies such as Visual Studio, Microsoft Azure .NET Core, and SQL Server
- Ideal student candidates will have experience in Visual Studio and .NET Core/C#
- Team Size: 2-3 students
- POC: Joe Morrison – Director, Product Management

**Note: NDA and/or IP agreement will need to be signed for this project.**

### [Design a Population Health Analytics Application for the Rural/Community Hospital Market]({{site.baseurl}}/projects/pdfs/Intalere Capstone Project_CheckNet_Aug2020.docx)

**Project Background**

Population Health Management refers to a concerted holistic approach to improving the patient health outcomes of a group of individuals within a community. The U.S. population health management market size was valued at 13.9 billion USD in 2019 and is anticipated to expand at a rate of 20.5% over the forecast period (2026). The market is majorly driven by the growing demand for healthcare IT services and solutions that support value-based healthcare delivery, resulting in a transition from Fee-For-Service (FFS) to a Value-Based Payment (VBP) model.

Some of the tenants of Population Health Management include:
- patient population profiling to assist with identifying patients at risk for readmission and create patient-specific care plans
- insights and information regarding social determinants and claims data
- patient risk scoring regarding health, lifestyle and medical history to create subpopulations through the division of a patient population
- empowering patients to have a higher level of engagement, education, and participation in their care

For this project, Population Health Management will provide the ability to target health trends, service utilization, health outcomes in key markets. It will help organizations to understand their community and the types of people who live there and the future services needed.

**Project Summary**

Students will aid in the development of features and analysis needed to provide a Minimal Viable Product (MVP) in the development of a Population Health Management module for rural and community healthcare providers combining patient claim data with census forecast data.

The application will utilize Experian CAPE demographics census forecasting data as well as needed patient claim data which will be combined to provide a rolling 5-year forecast of increase and/or decrease in patient categories grouped by disease state (i.e. Diabetes, Hypertension, Cardiac Disease)

The application will be built in the Microsoft Azure Cloud environment with end-user reporting, data visualization, and analysis provided via a Tableau Business Intelligence environment.

Students will also receive training and develop in a Domain Driven Design which is a methodology where developers work with the domain expert to visually create a model of the business domain. The business domain is the term used to communicate about concepts in the domain and all of the business rules in the domain. Students will gather information for the domain and graphical models from the domain expert and model it together. This graphical representation of the business domain helps everyone quickly understand the business domain, how things relate to one another, and drives the design of the software.



**Project Details**

Throughout this Capstone project, students will accomplish the following high-level goals:
- Complete Domain-Driven Design Training provided by Intalere
- Develop the project in an Agile development methodology  
- Gain real-world experience participating in a collaborative, product-engineering environment
- Research and engage with container technologies, including Docker and Kubernetes as well as work with additional technologies such as Visual Studio, Microsoft Azure, .NET Core, Tableau and SQL Server
- Ideal student candidates will have experience in Visual Studio and .NET Core/C#
- Team Size: 2-3 students
- POC: Joe Morrison – Director, Product Management


**Note: NDA and/or IP agreement will need to be signed for this project.**


### [CGI Client Onboarding Portal]({{site.baseurl}}/projects/pdfs/CGI_Capstone_Project_Proposal.pdf)
The processes of onboarding and knowledge transfer for new members on a project team are often challenging and have an impact a members’ project experience. CGI aims to improve the project experience of its members by facilitating effective knowledge acquisition & transfer processes which, in-turn, will help reduce project costs and shorten onboarding timelines.

In an effort to achieve this goal, we are looking to engage several students on a diverse team to build the foundation of a “client-project onboarding portal”. This portal will provide new team members with visibility into their assigned tasks while also enabling them to track their performance against these tasks, in order to be productive on their new projects. These onboarding tasks can represent formal trainings, required technology-stack-skills, and/or required paperwork.

**Project Overview**
To formulate and build a portal that will serve as an Onboarding and Knowledge Management solution, designed to make the process of onboarding new CGI members to project teams more efficient and effective. Students will work with a team of CGI experts to not only help solve this problem/challenge but also learn critical skills needed as they enter the workforce.

**Project Details**

The proposed Onboarding and Knowledge Management portal will achieve a couple of objectives:
- Provide a structured way for new team members to be onboarded to a project/team
- Provide the ability to track a team members progress against an onboarding plan
- Provide a platform where project knowledge can be captured, shared, and archived on an ongoing basis

The following non-exhaustive scenarios have been identified to achieve these objectives:
- A new or existing team member logs-in to the portal and is presented with tasks that have been assigned to them
- A project manager and/or lead can create and/or assign tasks to his or her team members
- A user’s ability to use a “Copy From” feature to duplicate and assign an existing task list to team members
- A reporting tool that enables project managers and/or leads track member progress and also review/approve the completion status of onboarding tasks

The outcome of this Capstone Project would be a software solution that meets these objectives, along with its associated artifacts like architecture documentation, user personas, user journeys/workflows, UI/UX prototypes, software development environment setup, code documentation, testing artifacts, etc.

Students should expect to learn about modern software-development techniques in an enterprise setting such as:
- Design-thinking methodologies
- Ideation and UI/UX rapid prototyping
- Agile software development
- Product and Project management

**Note: NDA and/or IP agreement will need to be signed for this project.**



### Deloitte - [Center for Disease Control and Prevention: Allocation of Funds and Education Resources to Combat Opioid Use Disorder (OUD)](https://canvas.pitt.edu/courses/46886/files/folder/privately_shared_projects)

Check canvas for the project description.

**Note: NDA and/or IP agreement will need to be signed for this project.**

## CS Faculty Projects


### RISC-V web based simulator for CS447

For DECADES CS 447 was taught using MIPS assembly language. However, MIPS processors are not that common anymore (RIP PS and PS2).
On the other hand, the RISC-V architecture (open-source) is gaining some momentum, and you can even buy some boards to have fun with it.

We are still using MARS (which we all hate ;), but we want to push the development of an alternative that uses RISC-V. wilkie developed a web-based alternative, but it's still not ready for primetime: https://gitlab.com/wilkie/rawrs
This tool is called RAWRS (RISC-V Assembler and Workable, Rewritable System) - it's an acronym it can mean whatever we want! - and it's a web-based tools (bye bye Java).

The objective for this project is to develop this tool further to a point where it can be used for CS 447.

The tool is written in (modern) Javascript where we predict most of the development will be focused. But you will also have the opportunity to stretch your assembly muscles. As the RISC-V simulator is backed by a RISC-V kernel :D

* Team Size: 3-4 students
* POC: David Wilkinson (wilkie) and Luis Oliveira


### Learning-based Resource Management on Heterogeneous CPU/Memory Systems

Computer systems are increasingly being used to support a wide variety of applications such as web browsers, social networks, email clients, audio and video players. Heterogeneous processors (i.e., different types of cores in a single CPU) and hybrid memory/storage systems (i.e., different types of memory accessible by the CPU) have been recently adopted by hardware vendors to balance performance and energy efficiency on computing devices. Still, the main research challenge for runtime systems software is to automatically allocate the execution tasks and associated data to the heterogeneous resources, while meeting user-facing performance targets with minimal resource consumption. Our research project will experimentally investigate and evaluate ideas to solve that problem, leveraging OS-level techniques, including profiling and tracing, and machine learning models that can help us characterize the application behavior from hardware-assisted performance monitoring counters. Specifically, students will learn how to use perf (a tool to monitor the performance of applications), deploy and run benchmarks to collect data, organize and clean the data, and experiment with different machine learning algorithms to extract policies for automatic resource allocation.

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux, C Programming, Python, Machine Learning
* Group Size: 2-3 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu) & Daniel Mossé (mosse@pitt.edu)


### Optimizing Web Browsing Energy Efficiency

While the Web has been around for decades and is available on practically every device from mobile phones to refrigerators, web browsing is a complex task that is still actively being researched. An ever-growing amount of mobile devices trying to stretch their battery life, in conjunction with increasingly complex web pages, create a delicate balancing act between energy efficiency and performance. Existing OS-based power management techniques designed to tackle this issue rely on generic system-level metrics that are unable to anticipate the complex behavior of a web browser, which can lead to energy inefficiency or poor user experience during web browsing activities.

In this project, we propose a new power management approach that leverages application-level information by interpositioning important functions corresponding to major phases in the web browser (Chromium in our study). This allows us to monitor the behavior of the application at a finer granularity (compared to OS schemes). Based on runtime observations, we can modify the web browser's behavior to evaluate the effect of different hardware mappings (CPU type and speed) on performance/energy usage. Ultimately, we seek to design a better method of mapping application phases to appropriate hardware usage patterns. We have already built the interpositioning and monitoring platform and now would like to design and implement our power management mechanism based on this infrastructure. This is an ongoing project initiated by Will Sumner and new students will be able to leverage his experimental infrastructure
(https://github.com/WilliamASumner/Chromium-Experiments).

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux, System Programming (C/C++), Python, Machine Learning
* Group Size: 2-3 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu)

### Experimenting with Disaggregated OS

Disaggregated hardware resources have recently been proposed as a way to allow flexible and efficient allocation of server capacity to large-scale applications. In this project, we would like to experiment with a research operating system for hardware resource disaggregation, called LegoOS (https://github.com/WukLab/LegoOS), released by researchers from Purdue University. LegoOS breaks the traditional monolithic server design into a network of independent hardware components (CPU, memory, disk, etc.). It splits the major OS functions into loosely-coupled monitors running on specialized hardware components, while fast network messaging is used to allow those components to communicate.

Experimentally we would like to understand how data-intensive applications spanning multiple machines could benefit, for instance, from the separation of the CPU from the memory system (DRAM disaggregation). For conducting our experiments, we will be using the CloudLab platform (https://www.cloudlab.us/).

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux Kernel, C Programming
* Group Size: 2 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu)


### [Build a Wireless Sensing Unit to Integrate Sensor Data with Virtual Reality for Balance Training]({{site.baseurl}}/projects/pdfs/Biehl_Project.docx)

Check the document, it has pictures in it. So I didn't include the text here.

* Team Size: 3-4 students
* POC: Jacob Biehl


<!--### A website for handing-in programming assignments


Tim Hoffman's hand-in system is behind the VPN. Due to so many students having trouble getting the VPN to work – he needs a workaround.  There are around 280 students and doing this by email by hand is very time consuming.

Perhaps a  structured Dropbox with course assignment id nested folders that can be script harvested and auto copied to a directory on AFS.

This is pretty vague and wide open since I have no ideas on a specific approach to get around the VPN.

If someone has a great idea I’d love to give them a shot at it.

* Team Size: 2-3 students
* POC: Tim Hoffman
-->

### Stephen Lee - two projects

1.	Project Background (exploratory):  The practical applications of Blockchains have evolved beyond cryptocurrency. Blockchain applications show promise in disrupting many sectors, including supply chain, energy, finance, etc. However, blockchain technology needs to overcome its scalability issue to enable widespread adoption. Today most blockchain technology support throughput in tens of thousands. This project will explore off-chain computation to improve the scalability of blockchains. In particular, we will integrate an existing permissioned Blockchain (Hyperledger Sawtooth) with a serverless computing infrastructure (ApachOpen Whisk) and study the impact of elasticity on performance.

Students are required to have strong programming skills and eager to learn new languages, including Go, Scala, etc.

* Number of students: 2-3

2.	Project Background (development): LIDAR sensors are becoming increasingly popular to capture semantically rich information. Google Earth is one such example, where lidar data is fused with a satellite image to present an interactive and immersive experience. The visualization tool also serves as a framework for other projects such as Google Sunroof Project and Maps. This project will involve developing a visualization tool for LiDAR data collected using aerial drones. We will use publicly available LIDAR data and satellite images to visualize building rooftops.

Students are required to have familiarity with HTML, Javascript, and python. Knowledge of any existing HTML/Javascript framework is a plus.

* Number of students: 2-3


### Polkadot - Visualization for bitcoin
Polkadot (https://polkadot.network/) is a heterogenous multi-chain; that is, it provides the ability for multiple different blockchains ("parachains") to share consensus and communicate securely with each other through a central relay chain.  Currently, while there are visualization tools for the relay chain (such as https://polkadot.js.org/apps/#/explorer/forks), and tools available for individual parachains, there are no tools that allow a user to have a cohesive view of the entire system.  The goal of this project is to produce a web application which will display the current status of the relay chain and various parachains in an easy-to-read format, including the last finalized block and current block candidates of the relay chain, status of various parachains, and status of the different parachains' message queues.

Ideally, this will start as a text-based system to ensure accurate collection of data, and then visualization features will be added to it.

This project will be especially interesting for people interested in blockchain technology or information visualization.

Technologies: This will mostly be done in JavaScript and node.js, along with display libraries of the group's choice and the Polkadot API.  However, it may require some code spelunking in the Polkadot Rust codebase.  We have team members that can assist you with all of these.

Team Size: 3-4 students
POC: Bill Laboon, Web3 Foundation Technical Education Lead (and Lecturer currently on leave from the University of Pittsburgh) - bill@web3.foundation

### Malihe Alikhani - three projects

- SCITalk: An Interactive Conversational Agent for Exploring and Visualizing Data

- BookTalk: An Interactive Conversational Mobile Application for Book Recommendation

- PittCoffee: A Smart Conversational Mobile Application for Placing Food Orders

POC: Malihe Alikhani



# Other university projects

## Green Guide Recycling Game

Pitt Sustainability want to make a game to teach people to recycle, compost, and donate on campus.

The Game Dynamic is expected to go like this: User should be asked to sort objects to the correct end-of-life option. When user gets it right they gain points, when they get it wrong a message appears with the correct answer. User can replay game as many times as they want. It may be fun to have a high score board on the game so people can compete to see who gets the most right answers in a set timeframe.

Below are just a few examples of possible scenarios that can be presented.
Scenario Examples

|Item|End-of-Life|
|-|-|
|Container strawberries come in from the store| Trash
|Torn pair of jeans|Textile recycling or thriftsburgh to be repaired|
|Shirt that no longer fits|Thriftsburgh|
|Dead batteries|On-campus battery recycling|
|Pizza box with grease|Trash|
|Cardboard box|Recycling|
|Single use plastic bag|Trash|
|Orange peel|Compost|
|Worn out sneakers|Textile recycling|
|Unopened Ramen you no longer want|Pitt Pantry|
|Almond milk cardboard container|Trash|
|Empty Ink Cartridge|Campus Mail to be recycled|
|Starbucks to go cup|Trash|


The plan is to embedded-in/link to the Student Green Guide and Employee Green Guide pages on sustainable.pitt.edu.

Here are some examples of similar ideas:
- UBC (Canada) – [yuluo.psych.ubc.ca/studies/Sorting_fun](yuluo.psych.ubc.ca/studies/Sorting_fun)
- Penn State Recycling Game (a but little slow): [https://recyclinggame.la.psu.edu/](https://recyclinggame.la.psu.edu/)
- Monroe County : [https://www2.monroecounty.gov/files/DES/education/SortItOut/index.html](https://www2.monroecounty.gov/files/DES/education/SortItOut/index.html)
- Virtual waste sorting game from UMBC: [quiz.tryinteract.com/#/5e999a59e1b7600014a65aec](quiz.tryinteract.com/#/5e999a59e1b7600014a65aec)
  - All of our answers aren’t the same on-campus, but in general the answers are reflective of Pitt and Pittsburgh’s waste diversion reality.

Team Size: 3-4 students
* POC (primary): Samantha Ford. Sustainability Projects Coordinator, University of Pittsburgh
* POC: Aurora Sharrard, Director of Sustainability, University of Pittsburgh


### Decision support - G2A policing

[presentation](https://docs.google.com/presentation/d/1WASMOi-arsi-bCEsv1pzwz5DPYz45skyGxLm_rCTJ_o/edit?usp=sharing)

This project aims at creating a website to help informing people and helping them navigate
through the difficult process of investigating police misconduct.

The application will help navigate the investigation procedure.
Many scenarios that can happen, but there are 6 parts to the police investigation
1. Complaint
2. Notification
3. Investigation
4. Conviction
5. Ex-post (what happens after conviction)
6. Record keeping

**Two parts**
This project has two distinct parts, and which ones you will work on depends on your interests.
So you can work on
1. Creation of the website tool.
2. Using Natural Language Processing to extract data from police union contracts.
3. A mix of both.

* Areas of Interest: Web-development, NLP
* Helpful Skills for NLP: Python, R, regex (or you'll need to learn them)
* Helpful Skills for web-dev: No restrictions, but useful to know JavaScript/Angular/Vue/etc.
* Group Size: 3-4 students
* POC: Sera Linardi (linardi@pitt.edu), Eliana Beigel
