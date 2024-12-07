# hPLUSDevEnvironment
## How to set up hPLUS development environment?
(1) Make sure that you have a Linux machine and hPLUS is installed on that machine. (Run it and see that you can log in to hPLUS).  
(2) Create the following folders.  
mkdir -p ~/hplusdev/src/main/java/logic/  
mkdir -p ~/hplusdev/target/classes/logic/  
(3) Create an IntelliJ IDEA project using the POM file available here and create soft-link in the project's folder.  
ln -s ~/hplusdev/src .  
(4) Now you can edit source files loaded from hPLUS in this project.  
