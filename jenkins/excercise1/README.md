# EXCERCISE1 - BOOTSTRAPPING
## TASKS
- Create the following GIT REPO Structure and add roles based access to the team. There is no automation involved in setting it up. Setting up the environment will give you great exposure on handling the core tools involved in DevOps. The following tools need to be setup.

1. GITHUB REPO
2. JIRA FREE ACCOUNT OR AZURE DEVOPS FREE ACCOUNT
3. JENKINS COMMUNITY EDITION (A Server or Docker Container). Preferably a VM running a jenkinsmaster.
4. SONARQUBE COMMUNITY EDITION (A server or a docker container.) A container will work. 
5. NEXUS OR JFROG ARTIFACTORY (A server or a docker container.) A container will work.

## CONFIGURE YOUR OWN SCM EITHER GITHUB OR AZURE REPOS OR GITLAB. CREATE THE FOLLOWING REPO FOR YOUR PROJECT WITH THE FOLLOWING BRANCHES.

    - main
        - dev
            - feature1
            - feature2
        - qa
        - prod
        - hotfix
        - refactor

- Feature Branches shall follow camel case sequence.
- Release tags shall follow 'v1.0.0' schema

- Create Dev, QA, Devops, Mgr, TechnicalArch users. Grant them access to the repos. Not all but to the ones they will be using the most.
- Create a JIRA/Azure Project with Agile Scrum or Kanban workflow. Grant them access to the project based on the roles they are going to follow.

- Setup Development environment on your local machine using the Angular App on Github. You can use the below mentioned public repository or you can fork any other application to your own github or any other SCM you are managing.

GITHUB : https://github.com/deepteshb/tourofheroes.git. 

- Create another user as DevOps on your local machine and setup your DevOps Folder.





*Note* : 
- No commits shall be allowed if they do not contain a Jira Ticket
- Noone else shall have access to master, dev, qa, prod and it shall only be accessible to authorised users.