# AWS_Host-a-Dedicated-Jenkins-Server-on-Amazon-EC2

<h2>Host a Dedicated Jenkins Server on Amazon EC2.</h2>

Following the steps you should follow

Step 1: Open your AWS console.<br><br>
Step 2: Search EC2.<br><br>
Step 3: Enter the name of the instance.<br><br>
Step 4: Select our virtual machine or Select operating system (sussgest free tier).<br><br>
Step 5: Then select instance type.<br><br>
Step 6: Then select your key pair (if you don't have a key pair, create and if you do, select it).<br><br>
Step 7: Select network settings.<br>
Click on the checkbox button to allow **HTTPS** and **HTTP** traffic.<br><br>
Step 8: Configure storage.<br><br>
Step 9: Then click on the launch instance.<br><br>
Step 10: Then we can see our instance is running.<br><br>
Step 11: Now select your instance. Now we can see an option called connect, so click on it.<br><br>
Step 12: Then click on Connect.<br><br>
Step 13: Now we can see the AWS terminal.<br><br>
Step 14: Now we are in our system.<br><br>
Step 15: To update our machine.<br><br>
Command for an update.<br><br>
```
sudo apt update
```  
Step 16: Now we install Java.<br>
**Note:** If you want to install Jenkins on your system, you must install Java. If you do not install Java, Jenkins will not run on your system.<br><br>
Step 17: Install Java.<br><br>
Command to install Java.
```
sudo apt install openjdk-8-jdk -y 
``` 
**Note:** 8 is a version of Java; if you want another version, you can...).<br>
Step 18: Now Java is installed on your system.<br><br>
Step 19: Install Jenkins.<br><br>
Step 20: Visit this website: [Jenkins Installation Docs](https://pkg.jenkins.io/debian-stable/)
Step 21: Step by step, we install Jenkins.<br><br>
Step 22: Then you all paste the command in the terminal, and your Jenkins is ready.<br><br>
Command to install Jenkins.
```
sudo apt-get install jenkins
``` 
            
Step 23: Check the Java version.<br><br>
```
java --version
```
Step 24: Now we start Jenkins.<br><br>
```
sudo systemctl start Jenkins
```
Step 25: Now we enable Jenkins.<br><br>
```    
    sudo systemctl enable Jenkins
```
Step 26: Check the status of Jenkins.<br><br>
```
    sudo systemctl status Jenkins
```
Step 27: Now we open our console.<br><br>
Step 28: Then we open our instance and copy the public IP.<br><br>
Step 29: Paste in the browser.<br>
**Note:** Our Jenkins server runs on port 8080.<br><br>
Step 30: We cannot open this just because we cannot set or pass any traffic rules.<br><br>
Step 31: Set traffic rules and go to security. Click on inbound traffic rules and change or add a new rule.<br><br>
Step 32: Add port 8080 to inbound traffic.<br><br>
Step 33: Now open the browser, and we can access it.<br><br>
Step 34: Now we can unlock Jenkins.<br><br>
Step 35: For that, copy the link from the Jenkins Unlock page.<br><br>
Step 36: Paste that (basically, it's a security code).<br><br>
```
sudo cat paste that unlock code
```        
Step 37: The terminal will now give you a secret key. Copy that and paste it on the Jenkins page to unlock it.<br><br>
Step 38: Now we operate our jenkins.<br><br>
Step 39: Then install the plugins.<br><br>
Step 40: Now Jenkins asks for the user name and password.<br><br>
Step 41: Click on Save and continue.<br><br>
Step 42: Now we can see Jenkins is ready, and we can see Jenkins dashbord.<br><br>





