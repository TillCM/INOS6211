# INOS6211
LAC and Resources for INOS6211

## LAC (Learner Activity Completion ) Task one:

*Make sure that you singed up for your VM*
[VM Sign up link](https://labs.azure.com/register/nzop2fh9)

# Connect to your VM with SSH (the secure shell) , you can read more about it [here](https://www.ssh.com/ssh/)
1. Access your VM using azure lab services [click here if you are lost](https://labs.azure.com). 


2.Start your lab 

![start your lab](/images/sshconnection.PNG)

3. select SSH as your connection method:

![Connect with SSH](/images/sshconnection.PNG)
*You will need to create a password at this stage*

4.open the command prompt (CMD) on your machine : *start -> Command Prompt*
![Connect with SSH](/images/commandprompt.PNG)

5.Copy the SSH connection from Azure
![copy SSH link](/images/sshlink.PNG)

6.Paste the link in your CMD
![paste CMD](/images/sshcmd.PNG)

7. Click Enter to connect
*Type yes to connect when asked*
*provide the password you set for your machine*
![connected SSH)(/images/connectedssh.PNG)

8. Install the tree tool [install tree](https://vitux.com/linux-tree-command/)

9.Create the following folder structure using the MKDIR and CD commands:
10.add the files using the touch command [touch command](https://www.geeksforgeeks.org/touch-command-in-linux-with-examples/)
[Create and Navigate folders in Linux](https://www.digitalocean.com/community/tutorials/basic-linux-navigation-and-file-management)

Here is some help:
[cd command](https://linuxize.com/post/linux-cd-command/)
[mkdir command](https://www.geeksforgeeks.org/mkdir-command-in-linux-with-examples/)


```├── postman
│   └── test_collection.json
│   └── test_environment.json
├── migrations
│   └── V01__Initial.sql
├── quickstart
│   ├── docker-compose.yml
│   └── docker-compose.override.yml
└── src
    └── Teamfu-be
        ├── appsettings.Development.json
        ├── appsettings.json
        ├── Controllers
        │   ├── ToDoItemsController.cs
        │   └── ...
        ├── Models
        │   ├── TodoItems.cs
        │   ├── ...
        │   └── TodoitemsContext.cs
        ├── Program.cs
        ├── Properties
        │   └── launchSettings.json
        ├── Startup.cs
        ├── Teamfu-be.csproj
        └── WeatherForecast.cs
└── Dockerfile
└── scripts
    └── entrypoint.sh

10. Use the tree command to display the folder structure 

11. Install Apache web server and configure your webpage [Install Apache on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04)







