
# Workshop for implementing/migrating Java web application on AWS with microservce, CICD and DevSecsOps

<hr>

## 0. Preparation
##### 1. Install all required SDK, packages in your dev environment
###### Mandatory
- Java SDK 8, Git client, 
- Maven (3.5.3)
- Eclipse Oxygen 3
- AWS plugin for Eclipse 
- AWS CLI in your development environment

###### Optional
- Install TM Terminal, Eclipse plugin (http://download.eclipse.org/releases/neon)
- Install YAML editor, Eclipse plugin

The installation time generally takes 10 ~ 30mins. Attendees should prepare all installations for their developing environment before starting this workshop.

##### 2. How to study this workshop
- Every module of this workshop covers one important topic, for example, how to integrate Paramter Store with your application, how to migrate application logics to Lambda and so forth.


- You will complete the application's features following the instruction of each module document but this document dose not promise to provide all kind of information to complete the application features for each module's objective. You need to search the documentation and figure out how to implement the codes required by module's goal.


- You can start from the source code of previous module except module-01, and fill the application out with proper source codes to meet the objective of each module.


- Sometimes, there are bugs in unit test intentionally to help you to understand the logics of application codes, it requires you should complete the code without errors.

<hr>

## [Module-01 workshop documentation](./doc-module-01.md)

<hr>

## [Module-02 workshop documentation](./doc-module-02.md)

<hr>

## [Module-03 workshop documentation](./doc-module-03.md)

<hr>

## [Module-04 workshop documentation](./doc-module-04.md)

<hr>

## [Module-05 workshop documentation](./doc-module-05.md)

<hr>

## [Module-06 workshop documentation](./doc-module-06.md)

<hr>

## [Module-07 workshop documentation](./doc-module-07.md)

<hr>


## [Module-08 workshop documentation](./doc-module-08.md)

<hr>

## [Module-09 workshop documentation](./doc-module-09.md)

<hr>

## [Module-10 workshop documentation](./doc-module-10.md)

<hr>

### Spring Cloud
https://cloud.spring.io/spring-cloud-aws/
Now Spring Cloud support S3, SNS, SQS, ElastiCache,CloudFormation and RDS

## git examples

git tag -l v1.1.*

git tag v1.0.2

git push origin v1.0.3

git clone

git checkout tags/<tag_name> 

git checkout tags/<tag_name> -b <branch_name>

delete tags

git push --delete origin <tag_name>

git tag --delete <tag_name>


## blog
1. Configuration - parameter store connection
2, Repository - Spring data