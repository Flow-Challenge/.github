# EOY Flow Challenge - Rules

## Overview

The **EOY Flow Challenge for Devs** is an exciting competition where developer teams will create two innovative projects: **PROJECT INITIALIZER TOOL** and **SNIPPET MANAGER TOOL**. Teams will utilize Flow for both coding and integrating solutions, employing a unique technology stack.

## Project Structure

1. **Project Components**:
   - Each project will be divided into two separate repositories:
     - **API Repository**: Responsible for the backend implementation using Flask.
     - **UI Repository**: Responsible for the frontend implementation using VUE.

2. **Team Formation**:
   - Developer groups will be created for each project.
   - Teams will be formed based on the technology stack they choose to work with (Flask for backend and VUE for frontend).

## Technology Stack

- **Frontend**: VUE.js
- **Backend**: Flask

This technology stack may differ from what participants are accustomed to, providing an opportunity to learn and adapt to new tools and frameworks.

## Challenge Rules

1. **Team Registration**:
   - Each group must register for one of the two projects: PROJECT INITIALIZER TOOL or SNIPPET MANAGER TOOL.

2. **Development Process**:
   - Teams must use Flow for coding and integrating their solutions. This includes utilizing Flow's capabilities for generating code snippets and managing project structures.

3. **Repository Management**:
   - Each project must maintain separate repositories for API and UI. Teams should follow best practices for version control and collaboration.

4. **Documentation**:
   - Teams are required to document their development process, including setup instructions, code explanations, and any challenges faced. This documentation should be included in each repository.

5. **Submission**:
   - Each team must submit their completed projects by the specified deadline. All code should be pushed to the respective repositories, and a final demonstration should be prepared.

6. **Evaluation Criteria**:
   - Projects will be evaluated based on functionality, code quality, adherence to the rules, documentation, and creativity in utilizing Flow within the solutions.

7. **Prizes**:
   - Prizes will be awarded to the top-performing teams based on the evaluation criteria.


## [1] PROJECT INITIALIZER TOOL

Overview
The PROJECT INITIALIZER TOOL is an innovative tool designed to streamline and accelerate the software project creation process. Similar to the popular Spring Initializer, this tool allows developers to choose the programming language, build mechanism, framework, and dependency libraries. With the help of FLOW AI, the tool generates a script compatible with Linux or Windows, setting up the entire project structure quickly and efficiently.

### Key Features
- Language Selection: Choose from popular programming languages such as Java, JavaScript, Python, Ruby, and more.
- Build Mechanisms: Support for multiple build tools, including npm, yarn, gradle, maven, etc.
- Popular Frameworks: Options to select widely-used frameworks like Spring, React, Next.js, Node.js, Django, etc.
- Dependency Libraries: Select necessary dependency libraries to ensure a complete setup from the start.
- Automated Script Generation: Generates an executable script for Linux or Windows to create the project structure automatically.
- User-Friendly Interface: An intuitive interface guiding users through the project setup process.
- Documentation and Examples: Comprehensive documentation and sample projects to assist users in utilizing the tool effectively.


## [2] SNIPPET MANAGER TOOL

The SNIPPET MANAGER TOOL is a powerful code snippet management application designed for developers. This tool enables users to create, modify, and delete code snippets easily. With integrated features powered by FLOW AI, users can generate new snippets using GenAI, automatically create tags for better organization, and manage their code snippets efficiently.

### Key Features
- Snippet Creation: Users can create custom code snippets tailored to their specific needs and programming languages.
- Edit and Delete Functionality: Easily modify existing snippets or remove them from the database when they are no longer needed.
- GenAI Snippet Generation: Leverage FLOW AI’s GenAI capabilities to generate new code snippets automatically based on user input or requirements.
- Automatic Tag Creation: Automatically generate relevant tags for each snippet using FLOW AI, enhancing organization and searchability.
- User-Friendly Interface: An intuitive and easy-to-navigate interface allows developers to manage their snippets with ease.
- Search and Filter: Quickly find specific snippets using search and filter options based on tags, languages, or content.








## How to push changes (create your personal access token)

1) Go to the user settings
![image](https://github.com/user-attachments/assets/65159a92-6ed8-4920-acbf-e49cf471ddbc)

2) Developers Settings > Personal access tokens > Tokens (classic)
![image](https://github.com/user-attachments/assets/1e0775df-90f2-4248-8ed9-1c59124cc414)

3) Generate new token > Generate new token (classic) > Copy the token 
![image](https://github.com/user-attachments/assets/753f02b8-5088-4313-91af-292250ad8cdf)

4) Clone the repo with your token like this
```
git clone https://<TOKEN>@github.com/Flow-Challenge/flow-centelha-initializr-api.git
git clone https://<TOKEN>@github.com/Flow-Challenge/flow-centelha-snippet-api.git
```

4.1) If you already cloned the repo, just set the url
```
git remote set-url origin https://<TOKEN>@github.com/Flow-Challenge/flow-centelha-initializr-api.git
git remote set-url origin https://<TOKEN>@github.com/Flow-Challenge/flow-centelha-snippet-api.git
```

