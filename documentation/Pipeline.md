#CircleCi

-CircleCi is used to automate the build, test and deploy for this project.

-In this project, a circleci folder and file of yml config will assist with the steps of deploying the application. The steps to deploy the app are as follows:

Push commits to your remote repository
prepare the environment variables
install Node.js and Install the correct NPM packages. Use NVM if needed.
install and setup aws cli & elastic beanstalk
install, build, and deploy front and backend of project
Backend is deployed to elastic beanstaslk and frontend is deployed to AWS services inside the S3 bucket.
