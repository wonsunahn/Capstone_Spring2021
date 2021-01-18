---
layout: page
permalink: /projects/
---

# Capstone Project List

<!--SO FAR: 57 (1 do mosse, 0 do alex)-->


Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Wednesday (26 August) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (28 August). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - Two projects

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


### [???]({{site.baseurl}}/projects/pdfs/NetApp-Pitt-Capstone-Abstract-Fall-2020.pdf)

**Check PDF** 

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
* Group Size: 1-2 students
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
* Group Size: 1-2 students
* Contacts: Daniel Mosse (mosse@cs.pitt.edu) and Vasco Xu (vax1@pitt.edu)

### Protect your voice in IoT voice devices


In this project we will explore software that keeps your voice private while asking voice assistants (like Alexa) for help with tasks.  We have created an environment that accepts Voice snippets and it tries to do speech recognition, translating to text (we call it the "utility").  Our software is successful if it can transform the voice snippets into another voice snippets (call it "defense") in which speech recognition is successful but an attacker cannot recognize whose voice it is (which would be an "attack").  The basic software environment will be set up in departmental servers to expedite results.  In this project we will carry out the following tasks (meet weekly and check code, data, results into github weekly):
1.	Read the paper describing the issues for Voice privacy
2.	Read and understand the software environment (what are the inputs, what are day of outputs, how inputs are read, what configurations exist, what are the different options for utility, defenses, and attacks)
3.	Reproduce early results
4.	Modify software to automatically collect and display more metrics (false positives, false negatives, etc.)
5.	Collect 5 more Datasets, run software, produce results similar to existing results but with new datasets (for all metrics)
6.	Collect and install more attacks (one more attack per student)
7.	Run software, produce results similar to existing results but with new attacks (for all datasets and all metrics)
8.	Analyze outputs
9.	Run sensitivity analysis of the various parameters
10.	Write report

* Areas of Interest: Internet of Things, security, privacy
* Necessary/Required Skills: Python programming, curiosity
* Group Size: 1-2 students
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


### Polkadot - 
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

### Ravi and Jacob
* Team Size: 4 students

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


### Aurora Sharard

1. Mobility assistance 

* Team Size: 4 students
* POC: Aurora Sharrard, Director of Sustainability, University of Pittsburgh

2. App for recycling

* Team Size: 4 students
* POC: Aurora Sharrard, Director of Sustainability, University of Pittsburgh

