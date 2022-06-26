# Spring Security
Spring Security is a security framework that secures J2EE-based enterprise applications, by providing powerful, customizable security features like authentication and authorization.

## The Need for Spring Security

* Spring Security is an open source security framework
* It supports authentication and authorization
* It can be integrated with Spring MVC and the Servlet API
* It supports Java and Kotlin configuration support
* It's easy to develop and unit-test the applications

## The Need for Spring Security

The Spring guys have already solved many security problems in spring security like,

* handling CSRF and making it convenient
* handling session fixation
* filters handle path traversal 
* handling RunAs functionality

So, when you will create your own filters, you have to implement all the Spring Security's features with your filters, but then you'd have Spring Security, wouldn't you?

Also See, [Why shouldn't we have our own filters](https://security.stackexchange.com/questions/18197/why-shouldnt-we-roll-our-own)

## Versions

[1.0.0](https://github.com/KomalJayswal/Basic-Spring-Security/tree/version_1.0.0)

[2.0.0](https://github.com/KomalJayswal/Basic-Spring-Security/tree/version_2.0.0)

## Pre-Requistics

Please install Java8 and maven in your system.

## Run Locally

Clone the project

```bash
git clone https://github.com/KomalJayswal/Basic-Spring-Security.git
```

Checkout to the branch version to be used

```bash
 git checkout <branchname> 
```

Go to the project directory

```bash
cd <project-folder-name>
```

Build the Project

```bash
mvn clean install
```
**_You can now see the repository build in your .m2 folder_**