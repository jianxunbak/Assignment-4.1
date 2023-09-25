### Preparation

This lessons are 100% conceptual learning. Be prepared to lead learners into activities to continuously engage them for learning.

### Lesson Overview

Before this lesson, learners had hands on experience with containerization. In this lesson, learners will learn about what DevOps is and this learning will follow them throughout the module. After this lesson, all other lessons are very hands on and is lesser on conceptual learning.

---

## Part 1 - What is DevOps?

We will recap what DevOps is according to the reading material reference [link](https://aws.amazon.com/devops/what-is-devops/) by AWS.

### Definition

> DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market. - https://aws.amazon.com/devops/what-is-devops/

<img src="./assets/devops.png" width="50%" height="50%"/>

### Principles behind DevOps
1. Maintain version control on all production artifacts. - Artifacts must be placed in a centralized version control system that is part of the CI/CD pipelines.
2. Implement CI/CD. - Teams deliver software updates and patches continuously, rather than on a calendar-driven deadline.
3. Automate acceptance testing of specifications of the system. - Teams should write and automate testing for the functionalities of the application
4. Enforce peer review processes. - Teams must review production changes collaboratively via a documented and systematic approach.
5. Create a culture of high trust. - No one should be afraid to ask hard questions, get into debates and take accountability. It gives teams the freedom to experiment with new tools and processes that can improve product delivery without fear of failure
6. Instate proactive monitoring practices - Create tailored reporting and alerts based on the configuration of the monitoring tools.
7. Foster win-win relationships across the organization. - Everybody is on one team, as neither development nor IT operations can succeed on its own.

### DevOps phases
1. **Planning** - The stage where development and IT operations teams -- along with other stakeholders -- determine the features desired, accompanied by an iteration value and criteria for each project phase.
2. **Code and build** - In the coding phase, developers perform their assigned coding work. When they complete their tasks, they check their work into a centralized source code repository which serve as the single source of truth for code. The build phase entails software code retrieval from the centralized repository and compiles the software code into a binary artifact, executes functional tests and publishes the artifact into a shared centralized repository.
3. **Testing** - Automation enables developers to achieve continuous testing to test multiple codebases in parallel. An automated testing strategy also ensures there are no flaws in an application's functionality.
4. **Continuous Integration** - The heart of the entire DevOps life cycle. It is a software development practice in which the developers require to commit changes to the source code more frequently.
5. **Continuous Deployment** - This is the stage where the code is deployed to the production servers. It is also important to ensure that the code is correctly deployed on all the servers.
6. **Continuous Monitoring** - This is the stage where vital information about the use of the software is recorded. This information is processed to recognize the proper functionality of the application. The system errors such as low memory, server not reachable, etc are resolved in this phase.

DevOps involves the organizational culture, practices and the relevant technological tools to achieve high application delivery velocity. The core of DevOps is the automation of Continuous Integration and Continuous Deployment.

### Benefits

As a class, let's put our answers together to by explaining the benefits of DevOps in our own words:

|# Benefit|Explanation|
|-|-|
|Speed|Input Answer|
|Rapid Delivery|Input Answer|
|Reliability|Input Answer|
|Scale|Input Answer|
|Improved Collaboration|Input Answer|
|Security|Input Answer|

### Culture & Practices

Break into groups to discuss about what kind of culture and mindset would foster the success of DevOps? Share your top 3 with the class.

|What Mindset|Why so?|Example|
|-|-|-|
|1. Your answer| Input answer|
|2. Your answer| Input answer|
|3. Your answer| Input answer|

What kind of culture and mindset would hinder the success of DevOps? Share your top 3 with the class.

|What Mindset|Why so?|Example|
|-|-|-|
|1. Your answer| Input answer|
|2. Your answer| Input answer|
|3. Your answer| Input answer|

---

## Part 2 - Technological Tools

> This section helps learner to expose to technological tools that may not be used within this module.

DevOps requires the use of multiple technological tools to make automation possible. Each software has its unique requirements and release strategies. Therefore, DevOps needs to garner the different technological tools to make automation possible.

<img src="https://shalb.com/wp-content/uploads/2019/11/Devops1-2048x1338.jpeg" width="50%"/>

### Activity - Research

Break into groups to research on what technologies or tool are being used by DevOps.

|# Name of Technology or Tool|How is it used?|
|-|-|
|1. Input answer|Input answer|
|2. Input answer|Input answer|
|3. Input answer|Input answer|
|4. Input answer|Input answer|
|5. Input answer|Input answer|

---

## Part 3 - Semantic Versioning

In the automated deployment process, known as Continuous Deployment, it needs to identify which image to pull from registry to deploy them. The unique identifier of the images are `tags`, which are typically version number. The most common versioning approach is `Semantic Versioning`. In short, [SemVer](https://semver.org/).

The versioning format is `MAJOR.MINOR.PATCH` (example: `2.1.5`).

1. MAJOR version when you make incompatible API changes
1. MINOR version when you add functionality in a backwards compatible manner
1. PATCH version when you make backwards compatible bug fixes

### *Activity - Research*

Break into groups, research on what the following pre-release labels means.

|Label|Meaning|
|-|-|
|Alpha| Input answer|
|Beta| Input answer|
|RC| Input answer|

### *Activity - Discuss*

Based on the given scenarios, discuss what should be the next version of the software.

**Scenario 1**

The current version is `2.1.3`. There is a new feature developed and two patches being fixed. There is no breaking change. What should be the next version?

**Scenario 2**

The current version is `2.1.3`. There is a breaking change that comes with three new features, and more than ten patches. What should be the next version?

**Scenario 3**

The current version is `2.1.3`. There are six new features. What should be the next version?


