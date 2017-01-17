# Webinar and Workshops

This repository contains a number of webinars and workshops that can be used to demonstrate ideas and concepts.

* Test Driven Cookbook Development
* Writing Great Unit Tests
* Managing Secrets with Chef
* Static Analysis
* Better Tools for a Better Life
* The Ruby Behind Chef
* Writing Elegant Tests

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


## Managing Secrets with Chef

### Abstract / Description

Managing infrastructure requires the coordination of many different applications and actors. Enabling secure communication between applications and the actors requires that a number of systems to trust one another. This means the distribution of keys, passwords, and certificates. When managing your infrastructure it can be difficult to maintain and distribute these secrets in a secure way.

In this webinar the facilitator will explain why it is important to manage secrets and how Chef is able to manage secrets through tools like encrypted data bags and Chef Vault. When we're done you'll understand the importance of security through encryption (over obscurity), how to securely manage those secrets with Chef, and know where to continue to build these skills.

### Agenda

* Create a Cookbook with a Secret
* Storing Data in a Data Bags
* Encrypting Data in Data Bags
* Encrypting Data in Data Bags with Chef Vault

### Workstation Setup

* Installation of ChefDK 0.10.10
* An instance able to run the `openssl` command
* A Chef Server
* A single node to bootstrap and apply a cookbook through Chef Server


## Static Analysis

### Abstract / Description

Static analysis refers to checks that are performed on code before it's run. It can be done by humans, in a code review, and with tools (also known as linting tools). The Chef Development Kit (ChefDK) includes a static analysis tool called Foodcritic. Foodcritic analyzes your Chef recipes to see if they conform to a set of rules and notifies you when it sees something, such as incorrect syntax, that violates a rule.

In this webinar the facilitator will talk about the benefits of using static analysis tools, of conducting code reviews and, in general, of maintaining common coding standards for your organization. We'll show you how to use Foodcritic and how to interpret its results. We'll also expand our scope a bit to include a more general linting tool called RuboCop. When we're done, you'll know why static analysis is a good idea, how to perform a code review, and be ready to use Foodcritic with your own cookbooks.

### Workstation Setup

### Agenda

* What is static analysis? Why static analysis?
* What is Foodcritic and how do I use it?
* What is Rubocop and how do I use it?

### Workstation Setup

* Installation of ChefDK 0.10.10
* A cookbook to examine with Foodcritic and Rubocop

> This content has no particular cookbook in mind. The slides introduce the concepts, the core commands, and a few flags but are not tied to a particular cookbook.


## Better Tools for a Better Life

### Abstract / Description

The infrastructure you manage with Chef is a complex machine. This complexity is mirrored in the cookbooks you develop and the data stored in your Chef server. It is an ongoing effort to keep track of the state of that machine and to keep up with all the functionality included in your (many) cookbooks. However, the right tools can help. With them, you can develop code faster, maintain cleaner code, and better understand your existing code.

In this webinar the facilitator will demonstrate how better editor and debugger tools can improve your work life. They will show you how the right text editor can make it easier to write code. Next they will demonstrate how tools like Rake and Guard can consolidate tasks and automate tests. Finally, he'll show you how Pry can help you to debug your recipes.

### Agenda

* Why Are Your Tools Important
* Exploring Features of a Modern Editor
* Capturing Common Tasks with Rake
* Automating Execution with Guard
* Debugging with Pry

### Workstation Setup

* Installation of Chef DK
* A Modern Text Editor

> This content talks about using a text editor to show off syntax highlighting, project / folder view, code snippets / plugin support, and keyboard shortcuts. A single editor can be used. To ensure reaching a wider audience more editors could be installed.

* An cookbook named 'httpd'. This cookbook that deploys apache, writes a simple html file, and starts the service. The actual contents of the recipe could be written demonstrating code snippets and keyboard shortcuts.

> This content has no particular cookbook in mind. The slides introduce the concepts, the core commands, and a few flags but are not tied to a particular cookbook.


## The Ruby Behind Chef

### Abstract / Description

Chef is built in Ruby - a conscious choice for its great flexibility and developer friendliness. For some people, learning the language can feel difficult because most examples lack your perspective as a Chef practitioner. In this interactive webinar, we invite you to follow along in your favorite editor as we dive through the source code to teach you core Ruby concepts.

Join us to learn:

- Fundamental Ruby concepts and how they create the Recipe Domain Specific Language and the tools that power Chef

- Pry’s ability to navigate and query source code

### Agenda

* Loading a Recipe File
* Evaluate Core Resources
* Evaluate Resource Blocks

### Workstation Setup

* Installation of Chef DK

> This content walks outlines concepts within the slides but does not give the steps to complete the work.


## Writing Elegant Tests

### Abstract / Description

You’ve probably found that the many tests you write for all your cookbooks require as much or more effort than maintaining the cookbooks themselves. You’ve also probably noticed that there’s quite a bit of boilerplate code required to verify all the recipes, resources, and helpers. The consequence is that much of your test code is duplicated from one cookbook to another.

In this webinar, Franklin Webber, Training and Technical Content Lead at Chef, will show you techniques that bring elegance to a cookbook’s tests. You’ll learn how to eliminate redundancy, rebuild common patterns into helpers, and extract those helpers into a portable library.

Join to learn how to:

- Refactor tests for more elegant code
- Craft reusable testing resources and helpers
- Extract testing resources into a Ruby gem

Who Should Attend:

- Anyone who writes tests for cookbooks

### Agenda

* let
* shared_examples
* def method
* shared_context
* require
* alias_example_group_to
* creating a Ruby gem
* questions
* wrap up

### Workstation Setup

* Installation of Chef DK

> This content walks outlines concepts within the slides but does not give the steps to complete the work.

* Clone the following repository: https://github.com/chef-training/elegant_tests-repo.git
