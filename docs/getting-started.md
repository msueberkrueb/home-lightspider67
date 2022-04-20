# Documentation of steps taken

## 1. Install NodeJS

Install the latest version of NodeJS from its webpage:

> https://nodejs.org/en/

NodeJS is a requirement for the following proceses. It's needed to run JavaScript or TypeScript locally
<br><br>

## 2. Install npm@latest

To install the latest version of npm type the following into a terminal:

> npm install -g npm@latest

This ensures that npm is at the latest version and can install the following packages
<br><br>

## 3. Install Angular

To install Angular, type the following into a terminal:

> npm install -g @angular/cli

This is the package that is needed for an Angular project
<br><br>

## 4. Create an Angular application

To create an Angular project, type the following into a terminal:

> ng new

This creates an Angular application and a basic project structure
<br><br>

## 5. Configure GitHub repository

To configure this GitHub Repository there have been multiple steps involved:

1. Create a **Public** repository
2. Push the local changes to this repository
   - For this, follow the instructions on GitHub when you open the newly created repository
3. Change the following Settings in the repository
   - General/Pull-Requests: Only allow squash merging
   - General/Pull-Requests: Always suggest updating pull request branches
   - General/Pull-Requests: Automatically delete head branch
   - Moderation/Code-Review: Limit to users explicity granted read or higher access
   - Branche/Branch-Protection: Create a new branch protection
     - Branch name pattern: main
     - Require a pull request before merging
     - Dismiss stale pull request approvals when new commits are pushed
     - Require review from Code Owners
     - Require conversation resolution before merging
     - Require signed commits
     - Include administrators

These settings should enhance the repository quality in the future processes.
<br><br>

## 6.
