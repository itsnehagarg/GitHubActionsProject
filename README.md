# GitHubActionsProject
Dive into GitHub Actions tutorial and hands-on

## GitHub Actions

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline.

## GitHub hosted runners


## Self-hosted runners
For Self-hosted Runners,

EC2
1. Create an EC2 instance.
2. Enable port 80 & 443 in SG Inbound rules.
3. Enable port 80 & 443 in SG Outbound rules.

For Self-hosted Runners, on GitHub

1. Settings-> Actions-> Runners-> Click on Add New Self-hosted Runner
2. Select the OS. 
3. Select the Architecture.
4. Token will be there. keep it secure
5. Run all the commands.
6. Go to your github actions file: .github/workflows/githubactions.yaml
7. Change the runs-on: self-hosted
8. 

## Interview questions

1. Why is your CI CD pipeline setup on GitHub Actions?
2. How do you setup GitHub Actions?
3. Explain the files (eg. yaml files) created while setting up GitHub Actions.
4. Explain pros and cons of using Jenkins and GitHub Actions.
