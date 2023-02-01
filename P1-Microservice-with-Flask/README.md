# Project 1 Cloud Continuous Delivery of Microservice (MLOps or Data Engineering Focused)
### Requirments of the Project
- Create a Microservice in Flask or Fast API
- Push source code to Github
- Configure Build System to Deploy changes
- Use IaC (Infrastructure as Code) to deploy code
- Use either AWS, Azure, GCP (recommended services include Google App Engine, AWS App Runner or Azure App Services)
- Containerization is optional, but recommended
### To do
1. Finish app.py
2. Set up continuous integration through a new workflow at Github
## Introduction
In this project, I built a small Microservice in Flask that calculates change. 
Dollar = $1, Quater = $0.25, Dime = $0.1, Nickel = $0.05
When you give a input of $1.2, it will return { "1": "dollars"}, { "2": "dimes"}.
- May change to the Chicken and Rabbit Problem.

## Structure Diagram
- to put the picture

## Preparation
### Setup files
1. Github Workflow
- todo
2. Requirments.txt
- Stores infomation about the libraries, modules and packages the program is built on.
3. Makefile
### App
1. app.py
2. test_app.py

## Deploy on AWS app runner
1. Containeriation: Setup virtual enviroment
2. Create a Microservice
3. Use AWS app runner to deploy code
- Todo: Use laC(Infrastructure as Code)
- 4 Steps
<img width="1199" alt="截屏2023-02-01 13 34 31" src="https://user-images.githubusercontent.com/84234596/216132654-0e126340-8fc6-4a44-a68b-4df954701cbc.png">
<img width="1212" alt="截屏2023-02-01 13 32 05" src="https://user-images.githubusercontent.com/84234596/216132700-0d71a149-6aaf-4d6a-8f5d-db6f3b2e817a.png">
<img width="1202" alt="截屏2023-02-01 13 32 53" src="https://user-images.githubusercontent.com/84234596/216132721-04eaeb57-05f4-416e-a864-e081fa09939c.png">
After clicking "Review and Create", it will turn to this page, and we can wait for running deployment.
<img width="631" alt="截屏2023-02-01 13 42 28" src="https://user-images.githubusercontent.com/84234596/216133874-eb287599-abb3-4afe-87a5-98b6dc5ec9f5.png">
Note: the deployment is failed here, need to check.
After the deployment, we can use the link to check app.py again.
