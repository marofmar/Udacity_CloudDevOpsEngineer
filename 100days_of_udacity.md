# Study Log: Udacity Cloud DevOps Engineer Nanodegree
#### Day 02: March 23 2020
* Begin to work on the first project, Deploy Static Website on AWS

#### Day 03: March 24 2020
* Reading AWS Ramp-Up guide Phase1 (https://d1.awsstatic.com/training-and-certification/ramp-up-guides/RampUp_Architect_102019_final.pdf)

#### Day 04: March 26 2020 
* Need to review from the basics..., starting to review Cloud Fundamentals lectures
* Lesson 1: Cloud computing 

#### Day 05: March 27 2020
* Working on Lesson2: Foundational & Compute service
* I have took the same lectures few weeks ago, but how can I forget this much in that short time period! In short, I am LEARNING! 

#### Day 06: March 28 2020
* Finished Lesson 2 and 3

#### Day 07: March 29 2020 Sun
* Working on Lesson 4, Security

#### Day 08: March 30 2020 Mon
* Finished LEsson 4 Security and working on Lesson 5 Networking & Elasticity

#### Day 09: March 31 2020 Tue
> Lesson 5
* Wroking on Lesson 5: DNS, autoscaling, load balancnig, 
* Route53: AWS Cloud Domain Name system. Also does health check
* Elasticity: servers, DBs, App resources automatically scale up or down based on load - no need to buy up front 
* Scale up (vertically  - assign higher RAM, IO, etc), Scale out (horizontally - adding more servers, etc)
* EC2 Autoscaling (In EC2)
* AWS Auto Scaling also exists apart from that of EC2 wihch works with Dynamo DB and so forth
* Elastic Load Balancing - provides redundancy and performance (In EC2)

> Lesson 6: Messaging & Containers
* SNS: Simple Notification Service
* SQS: Simple Queue Service , FIFO Queue when ordering is important
* ECS: Elastic Container Service

* Finished Lesson 6 and working on Lesson 7: AWS Management

#### Day10: April 1 2020 Wed
> Lesson 7
* Logging & Auditing in the Cloud - Visibility = > Cloud Trail
* Cloud Trail: Log ins, services accessed, actions performed, parameters for the actions, responses returned (Cloud Trail in Management & Governance section)
* Cloud Watch: a service that monitors resources and applications run on AWS (So, is it like the night-watch in GOT?!)
* Cloud Watch does: Collect and track metrics, Collect and monitor logs, Set alarms and create triggers, React to changes, etc.
* Infrastructure as Code
* Cloud Formation: Infrastructure as Code Service provided by AWS, written in JSON or YAML
* Lab - CloudWatch and CloudFormation
* Command Line Interface (CLI)

#### Day11: April 2 2020 Thur
> Project: Deploy Static Website
* Start!

#### Day12: April 3 2020 Fri
> I was charged more than 200 bucks,,,, from the account that I thought was in free tier... AWS...... Shocked.....

#### Day13: April 5 2020 Sun
> For the AWS account, I contacted Suppor team, and they solved the problem perfectly! I love you AWS,,,,, have my heart please,,,! 
* Let's get started Projet 1 !!!!!!

#### Day14: April 8 2020 Wed
> To deploy static website on AWS (Project 1) 
* Created and configured S3 bucket, distributed via CloudFront
* Confirmed the page is accessible via web browser, and submitted the project file! 

#### Day15: April 10 2020 Fri
> Started ch3. Deploy Infrastructure as Code
* Started L1. Getting started with CloudFormation
* DevOps = Development + Operation
`
DevOps is the combination of industry best practices, and set of tools that improve an organization’s ability to:
•	Increase the speed of software delivery
•	Increases the speed of software evolution
•	Have better reliability of the software
•	Have scalability using automation,
•	Improved collaboration among teams. 
`
