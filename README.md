
# Country-App-and-Rest-Api (Spring Boot Application with Angular UI)
This repository contains a Spring-Boot Rest API (with basic http CRUD operations) and a Angular material themed client application.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes

#### Running the Spring-Boot Rest API with IDE

* 	Download the zip or clone the Git repository.
* 	Unzip the Spring-Boot Rest API zip file.
* 	Open Eclipse.
	* File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip.
	* Select the project.
* 	Choose the Spring Boot Application file (search for @SpringBootApplication).
* 	Right Click on the file and Run as Java Application.

| Action|  HTTP Method | URL | Parameters |  
| ------ | ------ | ------ | ------ | 
| Add country| POST  | http://localhost:8080/rest/v2/country |{ "countryName" : "USA" } |
| Fetch all countries | GET | http://localhost:8080/rest/v2/countries ||
| Delete by Id| DELETE | http://localhost:8080/rest/v2/country/{id} |Id|
| Update country| POST | http://localhost:8080/rest/v2/country | { "id": 1 , "countryName": "UK" } 
## Running the Angular Client Application
#### Development server

Navigate to extracted to project folder and run `npm install` install the dependencies in the local node_modules folder and then run `ng serve` for a dev server. Then navigate to `http://localhost:4200/`.

## Technologies and Tools used
#### Client - Frontend/UI

* 	[Angular](https://angular.io/) - Angular is a TypeScript-based open-source web application framework.
* 	[Angular Material](https://material.angular.io/) - UI component infrastructure and Material Design components for mobile and desktop Angular web applications.

#### Server - Backend

* 	[JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) - Java™ Platform, Standard Edition Development Kit
* 	[Spring Boot](https://spring.io/projects/spring-boot) - Framework to ease the bootstrapping and development of new Spring Applications
* 	[Maven](https://maven.apache.org/) - Dependency Management

#### Others 
* 	[git](https://git-scm.com/) - Free and Open-Source distributed version control system













