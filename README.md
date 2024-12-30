# demo-github-action-workflow
Automation of continuous integration and continuous delivery using GitHub action workflow 

# create a respository
  - any name
  - syncronise any code editor (VS code) or github workspase
  - add License (MIT) and README.md

# create yaml file for automation process
  - .yml file save in .github/workflows directory
  - using git commands to commit to github respository

# yaml files
on: push
jobs:
    first_job:
        runs-on: windows-latest
        steps:
            - run: node --version
            - run: npm --version
