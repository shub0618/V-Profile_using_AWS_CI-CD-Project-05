# Repository Index

## Overview
Welcome to the AWS CI-CD Project! This repository contains the projects, scripts, and documentation organized into distinct directories.
That were done by me while pursuing my DevOps Course.

This `README.md` provides an index of all key components of the repository to help you navigate and understand the contents.

> IMPORTANT NOTE


> We have a product called V-Profile. It is a website written in Java. Consists of multiple services.
> We will be deploying this product on virtual machines and cloud platforms using differnt services.
> The same code or the product has been used for all the projects but with the different approaches based on the differnt use cases.

> NOTE: The code is not written/developed by me, this code is from my instructor who has designed this code for the differnet scenarios.


## Directory Structure

The repository is organized as follows:

```plaintext
├── Architecture/
├── META-INF/
├── aws-files/
├── src/
├── About_the_Project.md/
├── GitMigration.txt/
├── buildspec.yml/
├── pom.xml/
├── settings.xml/
├── .gitignore/
├── LICENSE/
└── README.md
```

## (AWS CI/CD Project)
In this project, we are going to use AWS services to fetch our code, build it and deploy it on AWS Elastic Beanstalk.
As you may have seen Jenkins CI CD pipeline, Same way we are going to create a code pipeline, but we are going to use AWS services for that.
We are going to migrate it from GitHub to Bitbucket.Then we are going to use AWS Code Build service, which is going to fetch the source code from Bitbucket
and deploy it on Beanstalk.

For the code Repository we are using 
- Bitbucket
  
We're using AWS cloud computing and the services that we are going to use In this project are: 
- Elastic Beanstalk
- RDS
- CodePipeline
- CodeBuild
- Cloud watch
 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


