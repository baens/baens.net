# Medici Ventures (August 2018 - )
## Positions Held
* Principal Developer

## Languages
* Java
* Python
* Javascript

## Frameworks
* React
* Spring Boot

## Platforms / Tools
* Git
* Make
* Maven
* Node.js
* Docker
* Kubernetes
* Terraform

## Technologies
* Vault
* Gitlab pipelines
* Google Cloud

## Accomplishments
* Successfully created a created continous delivery pipeline for all backend services. Went from a 2 day deployment process to a 30 minute deployment process. This process involed a merge-to-master code review process. Followed by a build process using gitlab. Which then deployed through environments using kubernetes manifests. 
* Migrated a production environment that was manually maintained through the Google Cloud Console to being maintained by Terraform. Used GitOps as the philosophy of how to control the production system. The deployment of the terraform scripts are under the same continious deployment processes as the backend service code. 
* Developed on the Bitsy Android application, creating several workflows around the banking information and buying screens.
* Developed features on the Java Spring Boot backend.

# Overstock.com (December 2015 - August 2018)
## Positions Held
* Principal Developer (February 2017)
* Senior Software Developer (December 2015 - February 2017)

## Languages
* Java
* Javascript

## Frameworks
* React
* Custom Overstock Java Frameworks

## Platforms / Tools
* Node.js
* Maven
* Webpack
* Docker

## Technologies
* Oracle
* 

## Accomplishments
* Presented at an internal conference called TechKno on "Docker"
* Was a major part of an internal tech evangelist team trying to change Overstock's culture to use more microservices. We advocated more adoption of Docker and Continuous Deployment. While the team may have not reach its goals, a lot of the practices were still be used and self adoption was.
* Was a major part of creating a Node.js platform for Overstock. This was a major accomplisment because at the time of my arrival, only Java was used as the deployment technology. Node.js broke a lot of barriers that allowed other technologies to also be adopted. By November 2016, the majority of HTML pages were being rendered with a Node.js service. The platform even surived multiple Black Fridays without a major problem. 
* Contributed to the main application that severed up Overstock.com.
* I architected and implemented with a team a CMS system that was needed for business to create content needed for the site without having to get a developer completely involved. The system was comprised of a React SPA internal website. A Java API Service interacting with a Oracle database. And a NodeJS server side rendering service. I was heavily involved with every piece of the system, and wrote the entire rendering and API.
* Started introducing a new architecture paradigm where universal rendering applications (NodeJS/React) are introduced in a very Java heavy monolithic architecture. This involved creating tools, systems, patterns, and training materials for other developers to use.

# RedCastle Resources (March 2007 - December 2015)
## Positions Held
* Senior Software Developer / Software Group Leader (June 2012 - December 2015)
* Software Developer (March 2007 - June 2012)

## Languages
* C#
* Java
* Python
* C
* PHP

## Frameworks
* .NET
* ESRI ArcObjects
* JUnit
* NMock
* Mockito
* Angular

## Platforms / Tools
* MSBuild
* Gradle
* Gulp
* Jenkins
* Git

## Technologies
* ESRI Technologies
* Redmine
* Trac
* Postgres
* MySQL

## Accomplishments
* Re­architectured a C#/Arcobjects application to better utilize lower­level APIs to achieve a 10x, and in some cases 100x, improvement in performance as compared to the built­in ArcMap processes.
* Turned a fire forecasting website into a self­serving website. We did this by embedded a Jetty server and all of the dependencies inside of the application. This lead to a more easily deployable app, making it possible to deploy the application multiple of times a day. Also made the application very easy to deploy in any new environment.
* Created a web viewer for live lightning data. There were a number of hurdles to overcome, including trying to get ESRI Arc Server and Oracle database to communicate correctly and learning how Oracle indexes spatial information to best achieve a usable web map.
* Been experimenting with a number of front end technologies (i.e. angular and ember). As well as been experimenting with a number of backend technologies (Java/Jersery and node.js/express).
* Expanded my understanding of RESTful architecture and hypermedia. Created a number of applications that used
* HAL to consume linkages from the server that exposed end points through the HAL protocol. This lead to being able to make URLs more maintainable with the goal of no more hard coding URLs inside of the client­side code.
* Was one of only 3 people of a 68 person company to achieve the title of "Senior".
* Maintained my good reputation for managing multiple projects with stake holders and clients.
* Managed a group of 4 developers. This involved putting together feature specifications and laying out a schedule with each developer for project deliverables and quality expectations.
* Built better communication between the developers and senior management to help better keep track of and maintain current project priorities and workload.
* Transitioned team to start making web applications based on front­end/back­end architecture.
* Successfully maintaining about 35 projects with 4 ­ 5 active at any one time. Have also been successful in marketing the team to bring in new projects.
* Balanced active development workload with management responsibilities.
* Taught myself C#, php, javascript, and ArcObjects to support mission critical applications.
* Maintained old php code bases. Took many of the ones that were going to have a longer life and refactored and cleaned up the code base to increase maintenance efficiency.
* On newer php code bases, started using CakePHP to help with standardization of code bases and speeding up development time because of usage of similar tools across code bases.
* Created a fire forecasting website on the Java Stripes framework. This site was started from a group of fire forecasters that wanted to standardize an excel application they had. It was proving to be more difficult to maintain, so they looked for a web application to be developed. The web application was deployed and has had great success with the community.
* Setup the company's first source control system (git), ticket/wiki system (redmine) and build server (hudson/jenkins).
* Maintained and created several application over the years. Time management and project management were guided by myself, and priorities were communicated with clients and stake holders to best create schedules and deadlines.

# Visual Influence (March 2006 - March 2007)
## Positions Held
* Developer (August 2006 - March 2006)
* Intern Developer (March 2006 - August 2006)

## Languages
* C++
* Bash scripting

## Frameworks
* OpenGL

## Platforms / Tools
* CMake

## Technologies
* CruiseControl.NET

## Accomplishments
* Developed a GPU memory management server that would help manage multiple processes that needed GPU memory. At the time, a global memory manager wasn't present on the GPU so you could easily run out of memory before the GPU would tell you. I created a process that would run along side our rendering applications to help manage how much memory was avaliable on the system. This was needed because for certain portions of the application, there were intense CPU parts and low GPU parts. So we could run batches of these applications to help speed up the process. 
* Developed applications and scripts to rapidly classify smoke from smoke stacks images for data mining operations. The application was built in C++ using OpenGL library. Two images were loaded which allowed a user to get them as close to overlapping as possible. Then a bash script was created to take a directory in a defined structure and load a pair of images for comparison. When the user felt the pictures were in the correct orientientation, a file was saved with image offsets. This image offset file was used to process the images through a data mining operation that compared the images to determine what the opacity of the smoke was. This was used to help an EPA project to determine if the smoke stack was classified in the right manner. 
* Setup, built, and tested servers to run test suite over multiple GPU architectures and allowed other developers to view outputs of test processes. 
* Oversaw the network services: DNS, CVS, build server, and was a network and system administrator of the five seats we had on the network.
* Added a visual orientation cube, giving people the ability to figure out where they were in 3D space.
* This required me to learn C++, OpenGL, and CMake.
* Got the build system working on Linux and Mac (was heavily based on win32 when I first got there).
* Helped maintain and upgrade a significant amount of the testing scripts. The testing scripts were used to take snapshots of what was being rendered, then compared them to a "gold" standard. I built utilities that allowed the other developers to write tests easier.
