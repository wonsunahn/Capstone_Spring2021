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



### Vinicius

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux, C Programming, Python, Machine Learning
* Group Size: 3 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu)

### Mossé

1+ projects usually in computer systems, energy efficiency

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux, System Programming (C/C++), Python, Machine Learning
* Group Size: 3 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu)

### Stephen Lee

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
* POC: Stephen Lee (stephen.lee@pitt.edu)


### Polkadot - 
Team Size: 4 students
POC: Bill Laboon, Web3 Foundation Technical Education Lead (and Lecturer currently on leave from the University of Pittsburgh) - bill@web3.foundation

### Malihe Alikhani - three projects


POC: Malihe Alikhani



### Ravi and Jacob
* Team Size: 4 students

# Other university projects


### Decision support - G2A policing

* Areas of Interest: Web-development, NLP
* Helpful Skills for NLP: Python, R, regex (or you'll need to learn them)
* Helpful Skills for web-dev: No restrictions, but useful to know JavaScript/Angular/Vue/etc.
* Group Size: 4 students
* POC: Sera Linardi (linardi@pitt.edu), Eliana Beigel


### Aurora Sharard

1. Mobility assistance 

* Team Size: 4 students
* POC: Aurora Sharrard, Director of Sustainability, University of Pittsburgh

2. App for recycling

* Team Size: 4 students
* POC: Aurora Sharrard, Director of Sustainability, University of Pittsburgh

