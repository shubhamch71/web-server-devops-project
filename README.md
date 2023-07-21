# web-server-devops-project
## This project is hosted on gitlab , you can access through the following link :- https://gitlab.com/shubhamc71/web-server.git
 Large scale webserver application programming and deployment using devops lifecycle(SDLC) PROCESS.
Software development lifecycle process.
Description:-


Source code is created using devlopers IDE & checked into "Gitlab" as our SCM(Source Code Management) or our CI(Continuous Integration) tool.


The source code is then checked out using "Jenkins Automation Server". Following stages as per CI/CD phases. The stages consists of the following


a. Checkout
b. Build
c. Release
d. Testing.
e. Deployment


Testing is performed on Test ENV which are configured using "Ansible(Configuration Management Tool)"


ENV created for Testing are built on "Docker" containers.


These containers are created on "Kubernetes" engine to provide large scale redundancy, scalability, monitoring & recovery.


Above infrastructure is based on industry standard DEV, UAT, SIT & PRD environments.


Above infrastructure is created with the help of Ansible & Docker using Jenkins Automation server.


Above process is covered with industry standards CI/CD pipeline from checkout till deployment phase including auto trigger from git to Jenkins.

