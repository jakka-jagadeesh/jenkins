# INSTALLATION OF JENKINS 

To continually create and test software projects, making it easier for developers and DevOps engineers to integrate changes to the project and for consumers to get a new build.

# steps for installing jenkins 

step 1  we have to update the packages 

' sudo apt update '

step 2 By using wget we can install jenkins 

' sudo wget '

[refer here](https://pkg.jenkins.io/debian-stable/jenkins.io.key)

step 3 install jenkins 

'sudo apt-get install jenkins'

step 4 start jenkins 

'sudo systemctl start jenkins'

step 5 To ensure Jenkins starts automatically on boot, run:

'sudo systemctl enable jenkins'

step 7 Configure Firewall (if necessary)  
it is compulsory to configure the app

'sudo cat /var/lib/jenkins/secrets/initialAdminPassword'

step 8 giving access to the jenkins 

'sudo cat /var/lib/jenkins/secrets/initialAdminPassword'

