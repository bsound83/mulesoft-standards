# TODO: Add MuleSoft Development Standards

## Source code structure

* catalog (folder)
    * catalog folder for custom types used in dataweave
* src (folder)
    * source code
* .gitignore
* README.md
* mule-project.xml
* pom.xml

## Creating MuleSoft Application Project

1. Create GitHub Repository
    * the name create for repo is used through application lifecycle
    * EXAMPLE: name = surepark-api (delimit name with hyphen)
        * repo name = surepark-api
        * project name = surepark-api
        * external properties folder name is surepark-api
2. Create Jenkins Jobs
    * SNAPSHOT
    * RELEASE
3. Create External Properties Folder
    * use mule.config.path to override for local testing
4. Create MuleSoft Project in Anypoint Studio
    * project must be mavenized
    * project should include a .gitignore file
5. Documentation
    * Make sure to update README.md file with relevant information regarding the application.
6. Source Control
    * Naming convention: always start with prefix of what we are coding:
        * TOPIC - default prefix when the items below don't match
            * "topic-initial" should be used on first iteration
        * BUG - use when a bug is found in application and a fix is needed.
            * "bug-update-customer-schema"
            * only represents a PRODUCTION bug / issue.
        * FEATURE - use when a change / enhancement is request from customer.
            * "feature-add-product-resource"

## Maven
Maven is the JAVA builder. 

Links: 
[Apache Maven Project](https://maven.apache.org/)

## Jenkins
Jenkins is our task manager.

Links:
[Jenkins](https://jenkins.io/)
[MAC Jenkins](http://jenkins.mspairport.com:8080)

## Nexus
Nexus is our binary library.

Links:
[Nexus - Sonatype](https://www.sonatype.com/nexus-repository-sonatype)
[MAC Nexus](http://nexus.mspairport.com:8081/nexus/#)