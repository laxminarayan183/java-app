# Java Web Application Deployment with AWS CodePipeline and Elastic Beanstalk

## Requirement
- AWS Beanstalk
- IAM role for Beanstalk `AdministratorAccess-AWSElasticBeanstalk`
- An GitHub repository to store your application bundle
- aws CodePipeline

## Steps
### step 1: create a github repository
### step 2: In That Repo add Files like,Push on github 
- buildspec.yml
- appspec.yml
- install.sh
### step-3: create a Beanstalk using tomcat
### Step 4: Create a pipeline with source github
### Step 5: Create build with other build
 - AWS codebuild
 - create project - instance,buildspec
### step 6: select deploy provider - AWS Elastic Beanstalk
### step 7: attach IAM policy to created role of java pipeline edit it and attach `AdministratorAccess-AWSElasticBeanstalk`
### step 8: go to Beanstalk and copy url paste it in browser
