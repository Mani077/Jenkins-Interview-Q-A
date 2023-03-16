# Jenkins-Interview-Q-A
1. How to downgrade/upgrade the Jenkins ?
Ans:
Go to jenkins check the version : Java --version 
Then go to usr/share/java
--cd /usr/share/java
--ls
Here you will find jenkins.war file
--> now stop the jenkins service 
systemctl stop jenkins
--> Now remove jenkins.war file
sudo rm -rf jenkins.war
--> Goto jenkins war download
https://updates.jenkins.io/download/war/
download necessary version using wget command on /usr/share/java
--> Now restart the jenkins 
systemctl restart jenkins
now login and log back jenkins 
it will changes jenkins version

### 2.Taking Backup and Restoring Jenkins Server.?

Goto manage jenkins --> Manage plug ins --> and install thin backup or periodic backup plug in 



