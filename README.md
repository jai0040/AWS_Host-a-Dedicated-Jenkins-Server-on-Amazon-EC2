# AWS_Host-a-Dedicated-Jenkins-Server-on-Amazon-EC2

Host a Dedicated Jenkins Server on Amazon EC2.

Following the steps you should follow

Step 1: Open your AWS console.
Step 2: Search EC2.
Step 3: Enter the name of the instance.
Step 4: Select our virtual machine or Select operating system (sussgest free tier).
Step 5: Then select instance type.
Step 6: Then select your key pair (if you don't have a key pair, create and if you do, select it).
Step 7: Select network settings.
Click on the checkbox button to allow HTTPS and HTTP traffic.
Step 8: Configure storage.
Step 9: Then click on the launch instance.
Step 10: Then we can see our instance is running.
Step 11: Now select your instance. Now we can see an option called connect, so click on it.
Step 12: Then click on Connect.
Step 13: Now we can see the AWS terminal.
Step 14: Now we are in our system.
Step 15: To update our machine.
Write a command for an update.
sudo apt update
Step 16: Now we install Java.
Note: If you want to install Jenkins on your system, you must install Java. If you do not install Java, Jenkins will not run on your system.
Step 17: Install Java.
Write a command to install Java.
sudo apt install openjdk-8-jdk -y (basically, 8 is a version of Java; if you want another version, you can...).
Step 18: Now Java is installed on your system.
Step 19: Install Jenkins.
Step 20: Visit this website: https://pkg.jenkins.io/
Step 21: Step by step, we install Jenkins.
Step 22: Then you all paste the command in the terminal, and your Jenkins is ready.
Write a command to install Jenkins.
            sudo apt-get install jenkins
Step 23: Check the Java version.
    java --version
Step 24: Now we start Jenkins.
    sudo systemctl start Jenkins
Step 25: Now we enable Jenkins.
    sudo systemctl enable Jenkins
Step 26: Check the status of Jenkins.
    sudo systemctl status Jenkins
Step 27: Now we open our console.
Step 28: Then we open our instance and copy the public IP.
Step 29: Paste in the browser.
Note: Our Jenkins server runs on port 8080.
Step 30: We cannot open this just because we cannot set or pass any traffic rules.
Step 31: Set traffic rules and go to security. Click on inbound traffic rules and change or add a new rule.
Step 32: Add port 8080 to inbound traffic.
Step 33: Now open the browser, and we can access it.
Step 34: Now we can unlock Jenkins.
Step 35: For that, copy the link from the Jenkins Unlock page.
Step 36: Paste that,
        sudo cat paste that unlock code (basically, it's a security code).
Step 37: The terminal will now give you a secret key. Copy that and paste it on the Jenkins page to unlock it.
Step 38: Now we operate our jenkins.
Step 39: Then install the plugins.
Step 40: Now Jenkins asks for the user name and password.
Step 41: Click on Save and continue.
Step 42: Now we can see Jenkins is ready, and we can see Jenkins dashbord.
