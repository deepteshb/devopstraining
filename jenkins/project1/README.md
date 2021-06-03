# PROJECT1
## PRE-REQUISITES
- Create the following GIT REPO Structure and add roles based access to the team.
    - master
        - dev
            - feature1
            - feature2
        - qa
        - prod
        - hotfix
        - refactor

- Branches shall follow camel case sequence.
- Release tags shall follow 'v1.0.0' schema

- Create Dev, QA, Devops, Mgr, TechnicalArch user groups
- Add atleast 1 user in each group
- Create a JIRA/Azure Project with Agile Scrum or Kanban workflow

- Setup Development environment using the Angular App on Github. Use the public repository or you can fork the same to your own repository manager like GitLab or Azure Repos

GITHUB : https://github.com/deepteshb/tourofheroes.git

## TASKS
- On a pull request to dev environment
    - trigger a job for BUILD, SCA, TEST, QUALITYGATECHECK
    - ensure code commits include the JIRA ticket.
- Store the project artifacts in a Project Repository like Nexus, Jfrog Artifactory or Azure Artifacts
- Tag the branch for a release with a predefined version.
- if any of the project artifacts are docker images, then push the image to docker repository after building the image using a Dockerfile.

*Note* : 
- No commits shall be allowed if they do not contain a Jira Ticket
- Noone else shall have access to master, dev, qa, prod and it shall only be accessible to authorised users.