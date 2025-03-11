# DevOps Interview Test: Design a CI/CD Pipeline for a Django Project

### Introduction

In this test, you are required to design a CI/CD pipeline for a Django repository using Github Actions. You will have complete freedom to decide which stages, jobs, and scripts to include in the pipeline, based on your preferences and best practices for CI/CD.

For context, let’s imagine that the Django Team has started working on a project for a client and that they need a pipeline to confidently show their progress to both the Project Manager and the client itself.

Your task is to clone the provided Django repository, create the CI/CD pipeline, and then grant us access to the repository.

The test is vague on purpose, we want you to design the pipeline based on what you think should happen from start to finish.

Feel free to include integrations with any third party software that you think would be useful.

### Prerequisites

- A Github account
- Familiarity with Github Actions
- Basic knowledge of Python-based web applications
- Familiarity with Docker

### Instructions
1.  Get a private copy of the challenge.

    Github does not allow private forks of public repositories so you can either:
    * Create a new private repo under your github username and push our challenge to your own repo
    * Use Github's import: https://github.com/new/import 
    
    You can find the repository at:
    
    ```
    <https://github.com/mrmilu/devops-coding-challenge>
    
    ```

    This way, you will have a private copy of this challenge to work on.
    
    
2. Design the Github Actions Workflow
    
    Create as many Github Workflows as you deem necessary.
    
    Design the CI/CD pipeline according to your preferences and best practices. 
    
    We love containers, an image should be built.
    
    You may also include any other stages, jobs, or scripts that you consider important.
    
3. Commit and push your changes

### Objectives

As you've already seen, this challenge is quite open-ended, we are specially interested in what you would do in a situation like this and don't want to limit you by choosing a specific path for you.
The end goal is to create a pipeline that ends up pushing an image to a registry, it's perfectly fine if you push it to a public registry, as there isn't any sensitive information on this repository.
As long as you reach that goal, feel free to choose any path that leads you there.

### Optional: Deployment Suggestions

As an optional step, you can include a brief description of how and where you would deploy the Django application. Some examples of deployment options include cloud platforms like AWS, Google Cloud Platform, or Microsoft Azure, as well as on-premises or self-hosted environments.

Feel free to describe any specific services, configurations, or best practices you would use for deploying the Django application.

We don't expect a working terraform project, just an outline of the services/technologies.

### Deliverables

- Your private github repo containing this repo, your changes and your designed Github Actions workflow(s)
- Access granted to `iker.blanco@mrmilu.com` to your repo.
- A markdown file named `DECISIONS.md` with an outline of your decisions so we can know why you did (or didn’t) do what you did :)
- A markdown file named  `TODO.md` with an outline of the things that you would implement, fix, upgrade if you had more time.
- (Optional) A brief description of your preferred deployment strategy for the Django application

### Questions

If you have any questions, feel free to email us at devops-candidates@mrmilu.com


Good luck! We're looking forward to reviewing your work.
