# Auth Microservice

## IMPORTANT NOTE

___Please read the project description thoroughly BEFORE getting started, especially the FAQs section.___

___Re-visit the project description multiple times DURING your design and development process, to ensure you're meeting the project requirements.___

## Problem Statement
We will build an authentication microservice, a health check microservice, and a client.

The auth service will have three primary features:
1. Sign in
2. Sign up
3. Sign out

<!-- ![api-gif](./api.gif) -->

## Objective
In this project, we aim to learn and practice the following:
* Designing, building, and deploying microservices
* Monitoring the health of microservices
* Setting up continuous integration
* Using gRPC to communicate between microservices
* Using session based authentication
* Writing testable code
* Organizing code using modules
* Navigating and contributing to an existing code base

## Terminologies

__Session based authentication__

[Session based auth](https://www.geeksforgeeks.org/session-vs-token-based-authentication/) works by giving the client a session token which can be used in subsequent requests to authenticate the user.

__Model__

Models describe how information is organized, transmitted or stored. In Rust models are defined as `enums` and `structs`.

## Recommendations
Here's a list of recommended action items to do during and after the development, to help you more effectively build the project and learn from the project.

During Development:
* You can either create your own Rust project and copy over the code in each step or clone this repo and finish the steps directly in this repo. 
* Check the project description/requirements to make sure you are building what is asked of you.
* Utilize the included unit tests to help debug your implementation.
* If you get stuck, ask for help in the Discord server or look at the next step for the solution to the current step.
* Refactor as you implement. Keep your code clean and compartmentalized. Doing so makes debugging exponentially easier, as your implementation grows.
* Make sure your code compiles and all tests are passing (if applicable) before moving on to the next step.

After Development:
* Run through the provided manual test cases (included in the Stage 3 README), and fix any bugs! You are almost done, so finish the project strong!
* Post your completed project on GitHub. You're a Rust developer now!
* Showcase your project to your friends and family (at the very least, to others in the Let's Get Rusty community)!
* After completing the project feel free to modify the program by changing the architecture, adding features, etc. This will help you make the project your own and better internalize the lessons you've learned.

## FAQs

__Will there a template to build the project on top of?__

Yes. Each step has a partially built Rust project for you to finish. Stages and steps build on top of each other until you have a completed project.

__Should my implementation look exactly like the solution?__

Your code may differ from the solution, as long as your code compiles, tests are passing, and the program works as intended you are in good shape. Also after completing the project feel free to modify the program by changing the architecture, adding features, etc.

__What if I get stuck and have questions?__

If you haven't already, join our Discord server and the exclusive Bootcamp channels as instructed on the Home page of the Bootcamp. Fire away your questions and find project partners over there!

__NOTE:__ `If you don't know how to implement a TODO item, look at the corresponding test to see what is expected.`

## Stages Overview
The project is split into multiple stages. Please keep in mind, some implementation choices are made to minimize the scope of the project, so we can focus on the learning and implementing Rust related concepts. Here's an overview of the stages:

### Stage 1

__Auth microservice__

In this stage we will implement the authentication microservice.

### Stage 2

__Client__

In this stage we wil implement a client that can call the authentication microservice.

### Stage 3

__Health check microservice__

In this stage we will implement the health check microservice which will monitor the auth microservice.

### Stage 4

__Deployment__

In this stage we will deploy the auth microservice and the health check microservice locally using Docker.

### Stage 5

__Github CI__

In this stage we will setup continuous integration for our 3 repositories (client, auth service, and health check service) using Github actions.

## Get Started!

Get started by navigating to Stage 1 and reading the README!