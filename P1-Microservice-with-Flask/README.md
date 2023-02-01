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
- Use laC(Infrastructure as Code)
