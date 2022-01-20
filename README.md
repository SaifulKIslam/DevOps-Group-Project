# DevOps Group Project

## Author
- Saiful Islam
- Ali Ataya
- Dondre Tyrell

### Links
- [Jira Board](https://dattt.atlassian.net/jira/software/projects/GP3/boards/2)

## Contents
- [Brief](#brief)
    - [Requirements](#reqs)
- [Project Planning](#planning)
    - [Jira Board](#planning)
    - [Collaboration](#services)
- [Architecture](#arch)
    - [Technologies Used](#tech)
    - [Reasons for using these Technologies](#reasons)
- [Risk Assessment](#risks)
    - [Initial Risk Assessment](#initialrisk)
    - [Final Risk Assessment](#reviewedrisk)
- [Technologies utilised](#tech)
    - [Reasons for using these Technologies](#reasons)
- [Things that went well](#suc)
- [Areas for improvement ](#improve)

<a name="brief"></a>
## Brief

The brief for the DevOps Group Project is to deploy an application for a 'Spring Pet Clinic’.

<a name="reqs"></a>
### Requirements 

The requirements for the project, which can be found on [QA-Community website](https://qa-community.co.uk/~/_/projects/final--devops) are as follows:

You will need to plan, design and implement a solution for automating the development workflows and deployments of this application. As part of your final deliverable you will need to discuss the project in a presentation and demonstrate these workflows

Using what you have learned consider the following:

-What tools will work for you best? For example: Terraform, Kubernetes, Ansible etc. There is no restrictions or requirements on which ones to use; you should decide which you feel are most appropriate and justify their use

-Multiple Environment support: How can a developer test their new features on an environment before merging their changes to the main branch?

-How can changes on the GitHub repository automatically build and deploy to testing and live environments?

-Running costs. What are your monthly estimates? How could they be improved?

<a name="planning"></a>
### Project Planning
To complete this project we chose to deploy the application via the use of Terraform, Kubernetes, Jenkins and Docker as well as using Amazon Web Services as our cloud provider

<a name="planning"></a>
### Jira Board

The project planning was done through a Jira board. This consists of a Backlog, sprint, MOSCOW order of prioritisation as well as items to check on completion. Updates were made to this board constantly throughout development. 

<img src="/images/jira.png"/>

<a name="services"></a>
### Collaboration

This wa sour first group project and so we tried to combine all of our knowledge and skills that we had gained so far in order to work together effectively. We used a [shared Github repository](https://github.com/AAtaya95/DevOps-Group-Project) where all of the other team members to become collaborators.

<a name="arch"></a>
## Architecture

<a name="tech"></a>
## Technologies Used

* Project Tracking: Jira
* Version Control System: Git(Github)
* Cloud Service: Amazon Web Services
* Containerization: Docker
* Version Control for Docker Images: Dockerhub
* Continous Intergration Server: Jenkins
* Orchestration Service for Containers: Kubernetes
* Load Balancing: Nginx

<a name=reasons></a>
### Reasons for using these Technologies

#### Jira
When it came to deciding which service we should use for our Kanban Board, the group agreed that Jira would undoubtedly be the best choice. This is because of Trellos ease of use and that each team member has the most experience with Trello over any other type of Kanban board. Trello also makes collaboration with others very straightforward.

#### Git(Github)
We decided to use Git as our VCS due to Git being the most popular VCS and it is also the VCS that we had the most experience with as a group. We chose to use Github due to its ability to allow seamless collaboration without compromising the integrity of the original project.

#### Amazon Web Services
We used AWS as our cloud provider to help increase our knowledge of AWS and the tools it provides. Although the team had more experience with using Google Cloud Platform, we still had some knowledge of AWS. We felt as though we should use AWS to help advance our comprehension of AWS and take advantage of the services it has to offer. We had also not used AWS in project work prior to this and we felt as though we had the confidence to challenge ourselves. The AWS services also seemed to be tailored better to fit our project aim. All of these things contributed to our decision to use AWS.

#### Docker
Docker is the container service that we chose to use for this project. As a group, we decided that it would be best for us to use Docker as we all had experience with the service from our previous projects. That coupled with the fact that Docker is the industry leading service for containerization and its rapid deployment process is why we opted to use Docker.

#### Dockerhub
The decision to use Dockerhub as the repository for our container images was a fairly simple one. We chose to use Dockerhub as all of the team members had an account and it was also the only version control for Docker images that we had experience with at this current time. 

#### Jenkins
Jenkins is the Continous Intergration Server that we decided to use for this project. We decided to use Jenkins due to our experience with the software, the fact that it is free to use and it is also easy to modify. The automatic build feature was also taken into consideration when we opted for the use of Jenkins. 

#### Kubernetes
The container orchestration service that we selected to use for this project was Kubernetes. We decided on Kubernetes due to its easy scalability and realiabilty. We had also not used Kubernetes in previous projects and felt that it would be good to attempt its use in this project.

#### NGINX
We used NGINX as our load balancer due to the teams previous expirience with using this software as well as the fact that it is simple to use, yet is still powerful.


<a name=risks></a>
## Risk Assessment

For the risk assessments we produced an initial risk assessment that was created before we began the project. Upon completion of the project we then went back to the initial assessment to review it and create our final risk assessment.

<a name=initialrisk></a>
### Initial Risk Assessment

Below is a screenshot of our initial risk assessment:

<img src="/images/initialrisk.png"/>

<a name=reviewedrisk></a>
### Reviewed Risk Assessment

Below is a screenshot of part of our final Risk Assessment:

<img src="/images/reviewedrisk.png"/>
