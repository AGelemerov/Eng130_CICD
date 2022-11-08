# CICD Pipeline and Jenkins

## Continuous Integration
Developers merge/commit code to master branch multiple times a day, fully automated build and test process which gives feedback within few minutes, by doing so, you avoid the integration hell that usually happens when people wait for release day to merge their changes into the release branch.
 - Developers merge/commit code to main branch multiple times a day
 - Fully automated build process - gives feedback in minutes
 - Fully automated test process - gives feedback in minutes
 - Avoids waiting for everyone to push to main at end of day as it is automatic
## Continuous Delivery
Continuous Delivery is an extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button.
 - Extension of continuous integration
 - On top of fully automated build and test process, release process is automated
 - Deployment is manual but one button click away
## Continuous Deployment
Continuous Deployment goes one step further than continuous delivery, with this practice, every change that passes all stages of your production pipeline is released to your customers, there is no human intervention, and only a failed test will prevent a new change to be deployed to production.
 - Extension of contunuous delivery
 - Every change which passes tests within production pipeline is released to customers
 - No human interaction unless a test has failed
 - Fully autonomous release

## CICD rundown

All about automating:
 - testing
 - deployment to stagin and production environment

## CICD tools
![cicdtools](images/Top-5-CICD-Tools-1024x558.png)

## What is a webhook
Webhook is a method of altering the behaviour of a webpage or web application with custom callbacks. These callbacks can be integrated and maintained by third party users or developers who may not necessarily be affiliated with the originating website or application.
## Jenkins
### What is Jenkins?
Jenkins is a self-contained, open source automation server which can be used to automate all sorts of tasks related to building, testing, and delivering or deploying software.
 - Great range of plugins available
 - Supports building, deploying, and automating for software development projects
 - Easy installation
 - Simple and user-friendly interface
 - Extensible with huge community-contributed plugin resource
 - Easy environment configuration in user interface
 - Supports distributed builds with master-slave architecture

## Steps
 1. Create a new CICD pipeline
 2. Generate new SSH keypair (ensure to generate it in .ssh folder on localhost)
 3. Copy `eng130_jenkins_angel.pub` to gihub repo
 4. Copy the private key in Jenkins
 5. Create job to test the CI

TESTING third