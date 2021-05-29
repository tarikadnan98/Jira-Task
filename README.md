# Jira-API Automation
This repo is for Jira assignment

# Tool Used

Apache JMeter Version 5.4.1

# About the files in this repository
1. Jira.jmx is the script file for JMeter.

2. image.png and 3MB.jpg are the two image files that is used in the API automation in JMeter.

# About cloning the repository

Download this repository as zip and unzip the file in JMeter Home directory e.g. E:\apache-jmeter-5.4.1\bin\

# General Instruction to run the script in JMeter
1. Open the Jira.jmx file in JMeter
2. In the "User Defined Variables" provide the following input as per your system settings

     a. Username: Username of Jira.
  
     b. Password: Password of Jira server.
  
    c. Lead: Provide a valid Lead username to whom the Project will be assigned.
  
    d. Server: Provide your Server IP of Name, e.g. 127.0.0.1, Localhost etc.
  
    e. Port: Port in Jira server is running.

3. Set your Jira "The total upload size limit of attachments" to 2097152 bytes (2MB) before running the script. You can find this setting in JIRA ADMINISTRATION >> System>> Attachments>> Attachment Size 
  
