# Webinar and Workshops

This repository contains a number of webinars and workshops that can be used to demonstrate ideas and concepts.

* Test Driven Cookbook Development
* Writing Great Unit Tests
* Managing Secrets with Chef
* Static Analysis
* Better Tools for a Better Life
* The Ruby Behind Chef

Below you will find an abstract, agenda, and the setup requirements for each of these experiences.

## Test Driven Cookbook Development

### Abstract / Description

Building cookbooks with tests will increase the speed at which you work by giving you consistent feedback throughout the entire cookbook development process. The Chef Development Kit (ChefDK) includes tools that allow you perform both unit testing and integration testing.

In this webinar the facilitator will explain what is unit testing and integration testing, how they apply to the domain of cookbook development, and demonstrate building cookbooks with a test-driven approach. When we're done, you'll know when to apply these two tools, how to use these tools effectively, and know where to continue to build these skills.

### Agenda

* What is Test Driven Development?
* Writing a test first
* Refactoring with tests
* How can I make your feedback cycle faster?

### Workstation Setup

* Installation of ChefDK 0.10.10
* Working Test Kitchen Driver

Everything is created from scratch within the demonstration.

## Writing Great Unit Tests with ChefSpec

### Abstract / Description

You're already building better cookbooks by incorporating tests into the development process but you want to move faster. Verifying a minor change takes minutes when you want it to take seconds. How can you achieve that fast feedback?

In this webinar the facilitator focuses on the power of unit tests. The show where they fit within a test-driven approach to cookbook development and demonstrates how they can speed up that process. Their tool of choice is ChefSpec. ChefSpec is a unit testing framework that allows you to write RSpec-style tests and its included in the Chef DK. At the end of the session, you'll know how to use ChefSpec to write great unit tests, and where you can go to improve your skills even more.

### Agenda

* Review Existing Cookbook
* Faster Feedback with Unit Tests
* Testing Resources
* Refactoring to Attributes
* A Quick Introduction to Debugging

### Workstation Setup

* Installation of ChefDK 0.10.10
* Working Test Kitchen Driver
* A cookbook named 'httpd' that has a default recipe that installs, configures, and starts the apache service with a single integration test that verifies a working web server.

> See the 'Review Existing Cookbook' section for the setup of the cookbook.
