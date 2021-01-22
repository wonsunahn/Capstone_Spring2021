---
layout: page
permalink: /projects/
---

# Capstone Project List

<!--SO FAR: 56 + 4Aurora +4NetApp-->


Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Wednesday (27 January) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (29 January). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - Two projects

 
**About NetApp**

NetApp is the Data Authority in the Hybrid Cloud.
Throughout the world, leading organizations count on NetApp for software, systems, and services to manage and store their data. We help enterprises and service providers envision, deploy, and evolve their IT environments. Customers also benefit from our open collaboration with other technology leaders to create the specific solutions they need.  
Our team is passionate about customer success. Our company culture and work environment support that dedication. Together with our global network of partners, we are united in one goal: to help our customers achieve the outcomes that matter most to them. To learn more, visit www.netapp.com. 
The project is driven by the Scale Out Storage team which provides the file system infrastructure within the kernel to achieve high performing, scalable containers that are a key component of the NetApp Data Fabric architecture.


### [Swagger UI Alternatives]({{site.baseurl}}/projects/pdfs/NetApp-Pitt Capstone Spring 2021.pdf)

**Check PDF** 

**Project Background**

In application development, RESTful APIs are an increasingly popular method of
exposing functionality to users. A well-documented API means that it is accessible by other
developers. For documentation to be useful, we will need it to be browsable and to be perfectly
organized for easy access. It is for this reason that writing good documentation may be tedious
and time consuming. By using a good visualizer to expose our API’s documentation, we can
save significant time for our API consumers.

Developers at NetApp have designed a RESTful API for our storage operating system
known as ONTAP®. These APIs are currently being exposed via Swagger UI. Our API
specification follows the OpenAPI standards, which allows our customers and partners to more
easily read, explore, test, and consume our API. This, in turn, makes it simple for anyone to
develop applications and scripts that are built on ONTAP!

For this Capstone project, NetApp is looking to explore a new visualizer that would help
fully expose our API’s documentation and provide a better user experience for consumers of
our RESTful APIs.

**Project Summary**

In this project, students will work on developing or enhancing an existing visualizer to
contain features like version management, searchable page, model filtering, customized styling,
auto expand object models and many more. The creative student team can propose additional
features in collaboration with the NetApp engineer lead.

**Project Goals**

• Develop two features: Provide a deep-search ability and version tracking.
• Assist with a plan to move these new features into production for ONTAP customers.
• Stretch goal – Provide additional functionalities based on team investigation.

**Project Details**
Over the course of this Capstone project, students will utilize several programming
languages and concepts, including:
• Working with HTTP to interact with RESTful software applications.
• Investigating the different third-party visualizers.
• Enhancing visualizer code to include the additional features.
• Working with React / JavaScript to create a new visualizer that satisfy all the criteria.
• Implementing object-oriented coding principles to design abstract templates used for procedural code generation.
• Using agile development.

* Team Size: 4 students


### [Develop a kernel extension for an Open Source File System]({{site.baseurl}}/projects/pdfs/NetApp-SOS-Pitt-Capstone-Abstract-Spring-2021.pdf)

**Check PDF** 


**Project Background**

Embedded and distributed systems focused projects are not commonly provided at a bachelor’s level Capstone project.  Our goal is to provide an opportunity for aspiring embedded systems engineers to gain experience in this area utilizing an open source embedded file system as a base for developing a specific kernel extension.
Developers at NetApp have been optimizing and enhancing our embedded proprietary file system (WAFL – write anywhere file layout) for over 20 years.  Because of the proprietary nature of the file system we will be using an open source equivalent for this project.   Working in the C language, students will gain real-life experience developing for embedded, distributed systems.

**Project Summary**

In this project, students will work with the FUSE open source file system installed on Ubuntu Linux platform. The project team will work through the detailed steps below to implement a kernel extension that reports the file system space usage.

**Project Details**

Over the course of this Capstone project, students will accomplish the following high-level goals: 
*	Download and install FUSE on Linux.
*	Work through a NetApp provided initial custom example to understand the basic architecture.
*	Create a read/write file system as an underlying test bed and explore the properties of this system.
*	Write the kernel extension (using the C programming language) to implement a user space reporting function.
*	Execute automated tests during the writing of the kernel extension.  Enhance the automated tests as necessary.
*	Enhance the file system to store user space consumed data in an in-memory database.
*	Update the in-memory database based on incoming fileops.
*	Implement a space enforcement feature which prevents write fileops that exceed a defined usage limit.


* Team Size: 4 students

### [CGI Client Onboarding Portal]({{site.baseurl}}/projects/pdfs/CGI-Capstone-Sprint-2021.pdf)

**Check PDF** 

**Project Overview**
To enhance and improve a client-onboarding portal that serves as an Onboarding and Knowledge Management solution, designed to make the process of onboarding new CGI members to project teams more efficient and effective. Students will work with a team of CGI experts to not only help solve this problem/challenge but also learn critical skills needed as they enter the workforce.

**Project Details**

The proposed Onboarding and Knowledge Management portal will achieve a couple of objectives:
* Support a structured way for new team members to be onboarded to a project/team
* Simplify the portability of the building and deployment of the application.
* Automate workflows where project knowledge can be captured, shared, and archived on an ongoing basis

The following non-exhaustive scenarios have been identified to achieve these objectives:
* The ability to build and copy templates of onboarding tasks
* Add ability to associate onboarding projects to client(s)
* Improve the application portability by dockerizing the application
* Improve the code quality using static code analysis from SonarQube

The outcome of this Capstone Project would be a software solution that meets these objectives, along with its associated artifacts like architecture documentation, user personas, user journeys/workflows, UI/UX prototypes, software development environment setup, code documentation, testing artifacts, etc.

Students should expect to learn about modern software-development techniques in an enterprise setting such as:
* Design-thinking methodologies
* Ideation and UI/UX rapid prototyping
* Agile software development
* Product and Project management
* State-of-art technologies

Students are expected to know or easily learn the following technologies:
* Java
* Spring-boot Microservices
* Angular
* Maven
* Docker
* SonarQube
* GitHub

Students who need to learn or ramp-up on any of these skills will be provided with materials. Also, CGI will provide Scaled Agile workshop to the capstone students. Currently, the onboarding application supports the following use-cases:
* Project Manager:
    1. Create projects
    1. Create members
    1. Create tasks
    1. Assign members to projects
    1. Assign tasks to members
    1. Delete tasks and projects
    1. Remove member from project
* New Project Member:
    1. View Assigned Tasks
    1. Start Task
    1. Complete Task
* Admin:
    1. Create Manager
    1. Delete Member


* Team Size: 6 students
* POC: Mohamed Farag (dr.farag@pitt.edu)

**Note: NDA and/or IP agreement will need to be signed for this project.**

## CS Faculty Projects

### RISC-V web based simulator for CS447

For DECADES CS 447 was taught using MIPS assembly language. However, MIPS processors are not that common anymore (RIP PS and PS2) (they still live in network equipment though :).
On the other hand, the RISC-V architecture (open-source) is gaining some momentum, and you can even buy some boards to have fun with it.

We are still using MARS (which we all hate ;), but we want to push the development of an alternative that uses RISC-V. wilkie developed a web-based alternative, but it's still not ready for primetime: https://gitlab.com/wilkie/rawrs
This tool is called RAWRS (RISC-V Assembler and Workable, Rewritable System) - it's an acronym it can mean whatever we want! - and it's a web-based tools (bye bye Java).

The objective for this project is to develop this tool further to a point where it can be used for CS 447.

The tool is written in (modern) Javascript where we predict most of the development will be focused. But you will also have the opportunity to stretch your assembly muscles. As the RISC-V simulator is backed by a RISC-V kernel :D

* Team Size: 4 students
* POC: David Wilkinson (wilkie) and Luis Oliveira

### Training KMeans relationally 

**Projects Background**

Based on a Kaggle study, most of the data used for training machine learning models are stored in a relational format inside a database. Therefore, in recent years companies and teams such as Relational AI and Google’s Bigquery ML have started implementing databases that accept relational inputs. Performing the join on the database tables is time-consuming and increases the size of the data due to redundancies that are factorized in a relational database. As a result, it will be faster to design and implement algorithms for training machine learning models without performing the join itself. One such algorithm for training KMeans relationally is proposed in [1] which consists of two sections. This project’s goal is the implementation of that algorithm.

**Project Summary 1**

The student needs to study and understand the algorithm in [1]. Then, the student should implement K-means++ algorithm from that paper in C++ and the code should be runnable on at least 3 relational datasets namely the Favorita grocery dataset, Yelp dataset, and Retailer’s dataset. There should be enough documentation and build instruction for the code. The code must be implemented efficiently, this means some aspects of the original algorithm will be slightly modified in the implementation, and the students will be instructed about the modifications needed. 
The steps are the following:
-	Study the relational algorithms including the algorithm in [1]
-	Download the datasets
-	Implementation of KMeans++ section of [1]
-	Writing the documentations for usage of the code

**Project Summary 2**

The student needs to study and understand the algorithm in [1]. Then, the student should implement the adaptive K-means algorithm from [1] in C++. The code should be runnable on at least 3 relational datasets namely the Favorita grocery dataset, Yelp dataset, and Retailer’s dataset. The students should assume the sampled centers in the weighting algorithm is given as an input to them. There should be enough documentation and build instruction for the code. The code must be implemented efficiently, this means some aspects of the original algorithm will be slightly modified in the implementation, and the students will be instructed about the modifications needed.
The steps are the following:
-	Study the relational algorithms including the algorithm in [1]
-	Download the datasets
-	Implementation of the adaptive KMeans section of [1]
-	Writing the documentations for usage of the code

> [1] Moseley, B., Pruhs, K., Samadian, A., & Wang, Y. (2020). Relational Algorithms for k-means Clustering. arXiv preprint arXiv:2008.00358.

* Team Size: 2 or 4 students (working on one or both projects)
* POC: Alireza Samadian (als417@pitt.edu)



### Online Profiling on Heterogeneous Memories

 Heterogeneous memory systems have been recently adopted by hardware vendors to balance high capacity and performance. Using recent OS support, as in Linux kernel 5.1+, the different types of memory (e.g., high-density/slow vs low-density/fast) can be seamlessly accessible by the CPU. A key challenge is to automatically allocate the application data to the most suitable type of memory. Our research project will experimentally investigate and evaluate ideas to solve that problem, leveraging OS-level techniques, including profiling and tracing, and learning-based models that can help us characterize the application behavior from hardware performance monitoring counters (PMCs).
 
In this project, students will learn how to use perf (a Linux interface to monitor the performance of applications through reading PMCs), deploy and run benchmarks to collect data, organize and clean the data, and experiment with emerging memory systems. Specifically, they will explore the “perf_event_open” API provided by the Linux kernel on Intel.
 
Students are expected to check code, data, results into GitHub weekly as well as to meet weekly to discuss progress. 
 
We envision the following (tentative) tasks for the project, with deadlines every 2 weeks, approximately:
 
- Read and understand the technical report describing the numap library using the perf_event_open system call [A Portable Library For Low-Level Memory Profiling](https://hal.inria.fr/hal-01408979/document) 
- Compile and run source code examples (written in the C language) using the numap library (also written in C) or libhugepagetune library (both use perf event open).
  * https://github.com/numap-library/numap
  * https://github.com/htfy96/libhugepagetune
 
- Use the libraries (and possibly modify it or modify the code calling it) to start/stop collecting memory memory addresses when running an application.  The collected addresses will be written periodically to an output file
  * Each sample should include: timestamp, type of memory operation (load/store), level of access (L1,L2..DRAM), address
 
- Analyze and validate your results/outputs (online mode) compared with the perf standalone tool (offline mode)
- Iterate, running more experiments as needed (eg, to validate a hypothesis that was created through the analysis)
- Document code and write a final report describing your findings, challenges, and lessons learned. 


* Areas of Interest: Operating Systems, Computer Architecture
* Necessary/Required Skills: Knowledge of Linux, C Programming, 
* Desired Skills: Python
* Group Size: 2 students
* POC: Diego Braga (dmoura@pitt.edu), Daniel Mossé (mosse@pitt.edu), Vinicius Petrucci (vpetrucci@pitt.edu) 

### Detecting Program Phases using Machine Learning


Applications usually are not totally CPU intensive or just memory intensive.  They go from one phase to another, multiple times. This project (longer descriptionhere) aims to characterize application phases and use machine learning to appropriately classify phases in an application. The goal is to schedule phases to the cores they are best suited for to achieve a balance between energy-efficiency and performance, for example, CPU intensive phases in powerful and energy-hungry cores while and memory intensive phases in smaller, power-efficient cores. Datasets and tools to collect more datasets will be provided.
 
We envision the following (tentative) tasks for the project, with deadlines every 2 weeks, approximately:
- Read and understand materials (papers, webpages) about leveraging hardware performance counters (PMCS) in heterogeneous scheduling to gain a general understanding of the field and previous work. 
- Compile and run our preliminary code (in Python) that uses some ML to detect phases.
- Analyze and validate your results/outputs (i.e., are phase predictions correct?)
- Iterate, running more experiments as needed (e.g., to validate a hypothesis that was created through the analysis)
- Document code and write a final report describing your findings, challenges, and lessons learned. 
 
 
* Areas of Interest: Machine Learning, Energy Savings
* Necessary/Required Skills: Knowledge of Linux, Python Programming
* Desired Skills: Machine Learning, preferably the ML course
* Group Size: 2 students
* Contacts: Daniel Mosse (mosse@cs.pitt.edu) and Vasco Xu (vax1@pitt.edu)

### Protect your voice in IoT voice devices


In this project, we will explore software that keeps your voice private while asking voice assistants (like Alexa) for help with tasks. We have created an environment that accepts voice snippets and performs speech to text with a pre-trained Neural Net (the software "utility") while simulating an attack that will attempt to perform voice recognition (match the voice ID of a person - the "attack").  In this environment, we explore how different audio data transformations affect both the utility and attack. Successful transformations (call it "defense") will allow the speech to text to be successful while inhibiting or hindering the attacker trying to match IDs. The basic software environment will be set up in departmental servers to expedite results.  This project will carry out the following tasks (meet weekly and check code, data, results in GitHub). We will be working with both:
1.	Read our brief summary from the book ["Profiling humans from their voice"](https://docs.google.com/document/d/1zk19-10_Mh2-i6d9JHZH7hqswCks7_A0PR2IZys_z9o/edit) describing voice privacy issues and [watching the video](https://www.youtube.com/watch?v=4HjcQjwKBWM) for a fast introduction. 
2.	Read and understand the software environment (what are the inputs, outputs, how inputs are read, what configurations exist, what are the different options for utility, defenses, and attacks). [Github with examples](https://github.com/Henrique-Potter/ppu-sound-experiment).
3.	Reproduce early results with the current [Tensorflow](https://github.com/tensorflow/tensorflow) and [Pytorch](https://pytorch.org/) Neural Net pre-trained models ([Speech2Text](https://github.com/mozilla/DeepSpeech), [Speaker Recognition](https://github.com/mravanelli/SincNet)).
4.	Modify the software to automatically collect and display more metrics (false positives, false negatives, etc.)
5.	Search and implement 5 more Datasets, run the software, produce results similar to existing results but with new datasets (for all metrics).
6.	Collect and install more attacks (one more attack per student). 
7.	Run software, produce results similar to existing results but with new attacks (for all datasets and all metrics)
8.	Analyze outputs.
9.	Run sensitivity analysis of the various parameters.
10.	Write a final report.


* Areas of Interest: Internet of Things, security, privacy
* Necessary/Required Skills: Python programming, curiosity
* Group Size: 2 students
* Contacts: Henrique Potter (potter.cs@pitt.edu), Daniel Mosse (mosse@cs.pitt.edu), and Stephen Lee (stephen.lee@pitt.edu)


### Solar-powered IoT cameras for video analytics platform

Advances in deep vision techniques and the ubiquity of smart cameras will drive the next generation of video analytics. However, video analytics applications consume vast amounts of energy as both deep learning techniques and cameras are power-hungry. 
In this project, we will explore techniques that will use reinforcement learning to turn the cameras on and off to reduce the energy footprint. 
We will explore how solar-powered cameras can learn policies to self-actuate to use energy sustainably. 
We have already developed a reinforcement learning environment/simulator for parking video applications. 
Successful completion of the project will involve integrating solar energy into this environment. 
Students will carry out the following tasks.

  1. Read the paper and understand the algorithms/techniques
  2. Understand and run the RL environment
  3. Reproduce the results in the paper
  4. Modify the architecture to incorporate solar charging of the cameras
  5. Run the same experiments with the new solar set up
  6. Collect more datasets and re-run the tests
  7. Analyze output and refine the architecture if needed
  8. Run sensitivity analysis for various scenarios and parameters
  9. Write the report summary
  10. Document and release the code and dataset

* Number of students: 3
* Required skills – python programming, and interest in machine learning
* POC: Stephen Lee (stephen.lee@pitt.edu)


### Polkadot Blockchain Statistics Dashboard

Web3 Foundation's vision to build the decentralized web - Web 3.0. One of the projects that W3F funds is Polkadot (polkadot.network), a heterogenous sharded multi-chain - essentially a group of blockchains which share security and interact through the medium of a central "relay chain". This relay chain is secured by a nominated proof-of-stake system, and for users, determining staking statistics can be difficult (although they are all available on-chain).  In the Fall 2020 semester, a group of students developed a node.js script which gives users much of this information.

The goal of this project is to take the script from the previous students and turn it into a "chain staking data" site. This will involve designing the page, setting up a node.js server, converting the script to run on the server, adding optimizations and additional features, and working with the DevOps team to deploy and manage it.

In this project, along with learning node.js and related web technologies, you'll also learn about the latest advances in blockchain technology and specifically Polkadot.

As Web3 Foundation is a strong believer in the open source philosophy, all software developed for this project will be open-source (Apache 2.0 license).

Team Size: 4 students
POC: Bill Laboon, Web3 Foundation Technical Education Lead (and Lecturer currently on leave from the University of Pittsburgh) - bill@web3.foundation

### Natural Language Processing for Social Good

Natural language processing methods, such as discourse analysis, argument mining, and BERT models, can be used to derive many useful insights from text published online. These insights can be applied to a number of different areas, especially the social science fields. Our main goals are twofold: to develop better NLP methods, and to use existing NLP methods to measure important social and political phenomena. Currently, we are working on measuring political polarization on social media for topics such as the coronavirus and the Black Lives Matter movement, by classifying tweets published over the past several months. We are also working on examining the impact of social media gatekeepers (users who disseminate news media to other users). You will learn to work with NLP tools and engage in design novel NLP models for social good. We aim to submit a paper to the SIGDIAL 2021 conference in March. 

* Number of students: 2
* POC: Malihe Alikhani (malihe@pitt.edu)

### A Conversational AI Framework to Fight Against Systemic Oppression

The 8-minute video footage of the event leading to Floyd's death has sparked mass outrage and protests across the US and around the world, but it was just one of the killings of unarmed Black people by police. African American and other racial and ethnicity minority groups are disproportionately targeted by a variety of police violence and abuse. In Pittsburgh, African-American communities continue to experience disparate policing. Pittsburgh's black population ranges between 23% and 27%, but accounts for 54% to 60% of the total arrests in recent years. Despite mounting evidence, it has been rare for police officers to be charged or convicted for excessive use of force. The lack of accountability and transparency about law enforcement misconduct has eroded public trust in policing in the local neighborhoods.

Existing systems to hold police officers to account for their misconduct and abuse are largely ineffective. A recent report showed that in Pittsburgh, nearly 15% new complaint cases were not adequately pursued. Meanwhile, the police unions negotiate contracts that give officers protection from discipline and accountability, and there are numerous known and obscure provisions in these contracts that block attempts of inspectors to discipline offenders and implement reform -- for example, restraining anonymous complaints. Moreover, research found that many victims of abuse are reluctant to file a police misconduct incident due to low trust in the systems. Many more were deterred from reporting due to the lack of sufficient knowledge to file a misconduct complaint (e.g. not aware of the meaning of misconduct, legal steps such as a sworn statement or affidavit to be taken, or the unnoticeable constraints written in the union contracts.) These systems have also left the victims of abuse with little support to seek justice and redress. There is a significant gap to be filled in supporting the communities in need.

**Aims. The goal of this project is to build tools that facilitate citizens' understanding of the process and rights of filing a police misconduct complaint, to recommend proper resources for seeking justice, and to increase transparency of the process.** We aim to build a novel intelligent system to assist ordinary citizens, especially people from minority communities, to understand their legal rights and the process of addressing police misconduct. A significant challenge is that we cannot presume that ordinary citizens have the knowledge about their rights or capacity to search relevant information as a legal expert might. To address this, we will develop a conversational agent based system (i.e., a chatbot) to make the complaint processes more accessible to the communities by integrating machine learning, natural language processing, and information extraction. In our system, a chatbot will answer users' questions by highlighting the text in the relevant documents with additional explanation in layman's terms. Our system will be freely available to the public with a hope to reduce the community's burden of additional investment in acquiring legal expertise.

* Number of students: 2
* Point of Contact: Yu-Ru Lin (yurulin@pitt.edu)

### Building AI Systems for Sign Language Interpretation

Sign languages are languages that convey meaning using the visual modality, through manual articulations in combination with non-manual elements such as facial expressions, body language. Sign languages, like other natural languages, evolved naturally through use and repetition by humans, without conscious planning, and are also governed by a set of linguistic rules. Moreover, sign languages developed independently of spoken language and do not share the grammar of their spoken counterparts. Different communities also use different sign languages that are often not mutually intelligible. 

Sign Language Processing is an emerging field of research concerned with how to automatically process and analyze sign language data, at the intersection of Artificial Intelligence, Natural Language Processing, Computer Vision and Linguistics. Applications include sign language recognition (recognizing the signs in videos), sign language production (generating videos of sign language words/phrases), sign language translation (translating sign language to spoken language), sign language segmentation (dividing signs into units). 

![Sign language production and translation]({{site.baseurl}}/projects/pdfs/signlanguage.png)

**Learning Goals**

In this project, you will learn how to perform data collection by web scraping for sign language data, and perform data preprocessing, including formatting and cleaning, on sign language videos and sign language textual annotations. You will also learn about the characteristics of sign languages and participate in the production of assistive technology for Deaf and signing communities.


* Number of students: 2
* POC: Malihe Alikhani (malihe@pitt.edu)

### Voice activated technology to improve medication adherence
Nearly 1/2 of the American adult population has been diagnosed with a chronic condition, but only 1/4 of prescriptions are being taken as they are prescribed. As a result, nonadherence places a burden of $300 billion on the healthcare system. Deployment of technology equipped with a pharmacist’s medication expertise into patients’ homes could be the tool the healthcare system needs to massively improve adherence rates. As mobile technology has grown over the past decade, the world patients are living in has become increasingly connected. However, the gap between patients and healthcare providers has not been bridged as efficiently as their connections. Mending this gap could save payers and the healthcare system millions of dollars on an annual basis.

Currently, key inefficiencies in the healthcare system lead to wasted opportunities that cost patients and payers money. A shift towards patient-focused care that is mediated by smart home technology will provide endless cost-saving possibilities. For decades, pharmacy has been geared towards reactive solutions to patient problems. Voice activated technology can accelerate healthcare’s shift towards a more cost-efficient, proactive approach. Payers have already started to notice the possibilities of a preventative approach, evidenced by the recent popularity of payer-provided health and wealthness programs. Incentivizing patients to take control of their own health is the key to a more successful and efficient health care system. Voice activated technology can be the backbone of medication adherence services and mediating a more transparent and hands-on approach to disease state management.

(Credit, Jared Murray PharmD 2021)

Milestones
* Start
  * Review of goals, expectations, and communication 
* Milestones
  * Review of platform documentation - Amazon Echo, most likely 
  * Review of clinical requirements - Recording patient adherence to a once daily medication 
  * Functional skill demonstration - Recognize “wake phrase”
  * Iteration/Refinement
  * Refined skill application - Perform specified recording of spoken message
* Final
  * Functional prototype of progressive effort 
  * Documentation of technical and clinical considerations throughout process
  * Summary video, screencast, and/or presentation of final outcome 

* Team Size: 4 students
* POC: Ravi Patel, School of Pharmacy (rmp40@pitt.edu) and Jacob Biehl (BIEHL@pitt.edu)



### Two sided recommendation webapp

Two-sided recommendations are generated by recommender systems when a "match" happens in response to preferences from two different sides (e.g., a customer and a business). This capstone project will build different web-apps, to help evaluate such a two-sided recommender system. In particular, we will need to build:
(1) a webapp for users (from both sides) to submit their preferences
(2) a webapp for users (from both sides) to evaluate/rate recommendations based on their preferences
(3) a webapp for expert users to evaluate/rate the provided recommendations (i.e., considering both sides)
(4) a webapp for expert users to create recommendations (can be thought of as a game).

The capstone project will be heavily data-driven. 

* Team Size: 3-4 students
* POC: Alex Labrinidis (labrinid@cs.pitt.edu) and Tahereh Arabghalizi (tahereh.arabghalizi@pitt.edu)

### TA assignment application

Scheduling TAs and UTAs to courses can be a complex problem, as it requires juggling student preferences, student availability, assignment  loads, recitation schedules, and departmental needs. This project aims at developing a tool that makes the lives of those involved easier: both students seeking appointments, and those responsible for the assignments. 

Your job will be to develop a Web Application that will cater to the needs all involved.

One part of the application will be the student profile. This will give students the opportunity to add all the data needed to assign them.
This will involve:
- Add course preferences
- Add schedule conflicts
- etc.

The other side of the application is the administrative tools. The design is still not finalized (that will be your job:) but these are the types of actions that should be possible to do:
 - Add prospect students
 - Add departmental needs
 - Assign students to recitations

 The last item is where your project will have the bigest impact. This project does not require you to come up with a fancy algorithm to automate the complete process. Instead, you will develop a tool that can give visual cues to its users. For example: highlight conflicts, show total progress, highlight recitations without TA, highlight TAs overloaded.
 As part of your project, you will be talking with Bill Garrison and Nick Farnan (the faculty curretly tasked with this process) to figure out different ways and tools that improve their experience assigning TAs to classes.

You will need to use a frameworks, sponsors are partial to Flask (Python) on the backend and React on the frontend. But open to other options that students would prefer/have experience with. 
The team can be split into frontend/backend development, so if students have an interest in purely one over the other (e.g., want JavaScript only), that should be fine. The frontend/backend subteams will have to carefully communicate to ensure compatibility. This approach would also allow us to easily hook in other scripts to manage the information gathered via the website by having the backend provide a flexible API to use.



* Skills you need to have/learn: HTML/JavaScript/CSS (or some framework)
* Team Size: 4-5 students
* POC: Alex Labrinidis (labrinid@pitt.edu), Bill Garrison (bill@cs.pitt.edu), and Nick Farnan (nlf4@pitt.edu)

### Virtual Kathy: A conversational agent for the CS Department.
This project will create a conversational agent (chatbot) to handle questions submitted to the CS department front office (e.g., where can I find Dr. X, do I need TOEFL for graduate studies, what is the admission process for the BS degree, is Y course offered, who do I contact for advice, etc). The project entails:
- creating training questions (by crowdsourcing them), 
- creating matching answers (some static / some through a database),
- setting up the conversational agent, 
- supporting "context" (i.e., follow-up questions), 
- routing non-answerable questions to humans, 
- testing the chatbot, and
- submitting the new questions and answers to step one to improve the system.

The capstone project will benefit from experience with NLP/chatbots/databases, but not required (i.e., you will need to pick it up).
* Team Size: 4-5 students
* POC: Alex Labrinidis (labrinid@cs.pitt.edu) 


<!--### Departmental - Tech - Manage combinations and room access
2-3-->

<!--### Departmental - Alumni website
2-3-->





# Other university projects


### 412Connect

**Project Background**

412Connect is a program that strives to connect Black-owned businesses with the university community.  We believe that this is mutually beneficial: consumers have much to gain from what these businesses have to offer, and these new consumers can make a difference for the businesses during these difficult economic times. 

We hope to do this by providing a web platform to:
* form groups of members of the university community that are interested in supporting Black-owned businesses
* provide recommendations on the  businesses to explore (will work with Black-business incubator Community Forge, Cocoapreneur and blackowned.pgh) 
* incentivize members to interact with the businesses, either by supporting them on social media (follows, likes, or posts), purchasing goods and services, and providing reviews of their experience (such as Yelp and Google Reviews). 
* make the experience really fun through points/ badges (possibly gift cards)

Each member and each group could track their engagement with Black-owned businesses through a dashboard. 

**Project Summary**

In this project, students will be working with the community engagement team to develop a full stack website to accomplish 412Connect’s goal of bringing more exposure to black-owned businesses in the Pittsburgh area. 

**Project Details**
* Tech Stack:
  * Front end:
    * JavaScript
    * HTML
    * CSS
  * Back end:
    * Django (Python)
    * Database

* Desired qualifications: Experience with Social Media Integration with APIs, backend/database management
* Group Size: 3-4 students
* POC: Sera Linardi (linardi@pitt.edu)


### Mobility assistance for pedestrians

In this project, you will build an application that uses CAPRIO's API to generate dynamic topological maps that help pedestrians navigate.

**Background**

If you remember your first day at Pitt, getting lost was certainly common. Maybe you needed to go from Victoria Building to Sennott Square and had no idea how to do it.
If you were at a large event that spawns multiple rooms, or even buildings, you probably have a similar experience. Google will definitely tell you how to do it, but it will give you a street route. Which you know, if you lived in Pittsburgh, that in Winter is not necessarily the best route.

Trying to solve this problem, [CAPRIO](https://db.cs.pitt.edu/caprio/) was born. CAPRIO combines indoors and outdoors information to give users a path that avoids the cold Pittsburgh weather. **_Oh, what if you need to avoid congested areas?_** Your brain may be wondering given the status of the world at this point in time. Well... the team behind CAPRIO thought the same, so CAPRIO can use congestion information to modify its path generation.

**Important**: The CAPRIO team will have some **limited** time to help you with issues connecting to CAPRIO. However, you will have to learn the software technologies to connect to them on your own.

**If that's all done, what is this project all about?**

Enter [Metro-style pedestrian maps](https://medium.com/@mateovtn/a-metro-style-pedestrian-map-for-uf-3c259d3adbf3) (topological maps). If you want to know how to move around Pitt, for example, these high-level topological maps are much more useful if you are a Human Being.
The problem is: _these maps are static, but the world isn't_. 

University events, classes, weather, and many other factors influence how people distribute themselves in buildings. Consequently, the best routes may change daily (perhaps even hourly). The available routes may even change if you have mobility issues! As such, having the ability to generate these maps given data about what events and paths are available to individual people is important and a great resource.

Your mission, if you choose to accept it, is to build an application that based on some user input (e.g. rooms/buildings of interest, date and time, mobility restrictions) queries the best paths from CAPRIO and generates a graph that represents the routes available from those points of interest. Then, using those graphs, display them to the user in a _Metro-style pedestrian map_.

* Skills you need to have/learn: MongoDB, HTML/JavaScript/CSS
* Team Size: 4 students
* POC: Aurora Sharrard, Director of Sustainability, University of Pittsburgh


# Bioinformatics projects

### Single-Cell RNA-Sequencing

Single-cell RNA sequencing (scRNA-seq) provides the expression profiles of individual cells and is known for defining cell states and phenotypes.  Students will be performing a Single-Cell RNA-Seq Analysis using a set of analysis pipelines known as Cell Ranger.  The team will be assigned to find and download a publicly available data set and upload that data to a high-performance computer cluster (HTC).  To perform the pipeline, students will be learning how to access and utilize high-performance computer clusters to process data in Unix.  Students will learn how to use and customize the Cell Ranger pipeline to accurately process the data.  Once the data has been processed, the results will be imported into R.  From there students will utilize the R Package, Seurat, to analyze the data using statistical methods.  Students will also be required to learn other R methods to visualize their results from the Seurat output.  Upon completion, students should be able to smoothly run the Cell Ranger pipeline and have an overall understanding of final statistical output from the R package, Seurat.
Note: We recommend students with no Unix/Command-line experience to attend the “Introduction to Linux for NGS” Workshop provided by Pitt’s CRC.  It is a 3-hour workshop that will cover Unix basics and how to access HTC, the high-performance computer cluster.  Info on the workshop can be found here, and is listed as “Introduction to Linux for NGS”:
https://crc.pitt.edu/training/spring-2021-next-generation-sequencing-workshops 

* Team Size: 3 students
* Recommended Skills: Unix/Command-line Experience, General Understanding of R/R Packages, Basic Understanding of Statistics, Foundations of Biology
* POC: Alexander Chang (ALC217@pitt.edu)

### MedWISER - user-controlled clinical data web application


**Project Background**

A major problem for doctors and nurses is that current electronic health record (EHR) software is extremely complex and makes them click around many different menus and screens, so when diagnosing a patient they can’t see all the relevant information together.  This is dangerous, as they can forget things or not see relationships between data; which affects their diagnostic and treatment decisions; it is also tiring and frustrating so they get burnt out.

FHIRtiles is a medical program written in Angular, that gets data from electronic health records and lets the user arrange ‘tiles’ in different ways, with different visualizations.  There is a new API system (that the government mandates) that gets data from the EHRs, which allows us to build nice applications on top of it, to make the doctor’s work easier.  Users can gather information together on the same screen, visualize it in different ways, share with colleagues and so on.  

This could have big effects in speeding up medical work, diagnosis and treatment, as well as adjusting software fast when new diseases arise.

**Project Summary**

Extending the tiles program to include nice visualizations useful to doctors.  The current program has somewhat crude front-end, and does not include all the data needed.  Some specific visualizations like sparklines and timelines would be useful, as well as whatever the students design for original uses.


**Project details**

The work here would involve parsing json data from the API (and there are tools that make that easier), putting it into the tiles program, and figuring out nice ways of displaying it (I can give guidance and we are starting an international collaboration about this but you are also free to find creative ways on your own that meet the needs of doctors.  If nicely done this could actually be used in a clinic. It should be easy to use for people without programming background, like a consumer app.  I will explain more in the meeting.


* Team Size: 2-5 students
* POC: Yalini Senathirajah


### Poholek Lab - Unbiased determination of Promoter Chromatin H3K4me3 elongation in tumor immunity

The tumor microenvironment suppresses anti-tumor immunity and is a major barrier to immunotherapeutic strategies. One mechanism of anti-tumor immunity is the prevalence of normally cytolytic CD8 T cells exhibiting a state of functional “exhaustion” characterized by reduced effector cytokine expression, proliferative potential and metabolic dysfunction. Using a low input assay termed CUT&RUN we have profiled the chromatin landscape of progressively exhausted CD8 T cells from murine tumors. K4me3 is an epigenetic mark associated with active promoters and gene expression. Broad distribution of K4me3 has been associated with tumor suppressor genes and transcriptional elongation and gene expression changes (Dai Z et al, Nature Comm 2018; Chen K et al, Nat. Genetics 2015). This project would aim to determine in an unbiased manner if H3K4me3 deposition was differentially elongated in exhausted T cells, potentially contributing to gene expression changes associated with loss of effector function and anti-tumor immunity. Datasets are in hand and students would use the above references papers as a guide for how to parse chromatin data but peak width as well as compare to gene expression data. Should the data be of interest, they may be included in a manuscript in preparation on the larger question of epigenetic regulation of T cell exhaustion in the tumor. A major goal of this project is not only to determine the biological answer of H3K4me3 but also to graphically represent it in a simplified manner for presentation. 

* Team size: 2-4 students
* POCs: Rhodes Ford, PhD candidate PMI; Amanda Poholek, Assistant Professor, Department of Pediatrics. 
