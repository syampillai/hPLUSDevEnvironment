# hPLUSDevEnvironment
## How to set up hPLUS development environment?
(1) Make sure that you have a Linux machine and hPLUS is installed on that machine. (Run it and see that you can log in to hPLUS).  
(2) Create the following folders.  
mkdir -p ~/hplusdev/src/main/java/logic/  
mkdir -p ~/hplusdev/target/classes/logic/  
mkdir -p ~/hplus/so/jars/  
mkdir -p ~/hplus/so/ext-jars/  
(3) Copy hdev jar to ~/hplusdev folder.  Also, all ext-jars mentioned in the POM file (you can download from in this project if required) should be copied or soft-linked.  
(4) Create an IntelliJ IDEA project using the POM file available here and create soft-link in the project's folder.  
ln -s ~/hplusdev/src .  
(5) Now you can edit source files loaded from hPLUS in this project.  
