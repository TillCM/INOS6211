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
```
10. Use the tree command to display the folder structure 

11. Install Apache web server and configure your webpage [Install Apache on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04)

# INOS6211 LAC 2: 

## Understanding the Linux boot program 
This video explains to you how Linux (any operating system really) boots. 

 [Understanding the Linux Boot Process](https://www.youtube.com/watch?v=mHB0Z-HUauo)
 
 [Understanding the POST proccess](https://www.youtube.com/watch?v=PSnGuvylWBI)
 
 [Common POST Beep codes](https://www.pcmag.com/encyclopedia/term/beep-codes)
 
Watch these videos and create an infographic to explain the boot process visually 
Here are some nice free infographic tools 

[CANVA](https://www.canva.com/)

[PIKTO CHART](https://piktochart.com/)

*Textbook ref : p17-27*

## Understanding how Linux is installed:
Find a good web source that takes you through a step by step guide to install Ubuntu
1. Create a cheat installation guide that is no more than one page long. 

We will look at Chapter two once our VMs are through the firewall. 

## Peforming Basic Linux tasks *p79*
*You are very welcome to use the internet to help you - and you can look in your manual(internet is more up to date)
I need you to open your terminal ctrl+alt+T and issue the following commands*
1. the ls command to show the files and folders we created in the last lac 
2. the ls command with the  -l switch (ls -l) to show the permissions assigned to the folders
3. the date command that shows the day of the mothn, the hours in the 24 hour format and they year in 4 digits 
4. show the calender with the cal command
5. run the uptime command
6. figure out wh oyou are logged in as 
7. find the hostname of your machine
8. show who is currently logged in 
9. show ebveryone that has ever logged in 
10. echo out the message "I love Ubuntu"
11. show the contents of the /ect/default/grub file with line numbers using  cat


## LAC3:

# Working with the Linux filing systems and Hard drives 

### Step 1 : Learn to Dual boot with Linux:

1. Add an extra 10GB Harddrive to your machine

[Add HDD Hyper_V](https://manuals.gfi.com/en/exinda/help/content/exos/virtual-appliances/hyper-v/hyperv-locate-vhd.htm)

2. Watch the following video to allow Ubuntu to recognize the drive  

[Mount HDD Ubuntu](https://www.youtube.com/watch?v=jZVs-SInMBU)
*we are using Hyper-V watch the video above to add hour HDD*


#### Do not use your class VM for this ! Create a new one !!!
4. Use the following tutorial to dual boot and partition a Linux system:

[Dual Boot and Partition Linux](https://www.tecmint.com/install-ubuntu-alongside-with-windows/#:~:text=In%20the%20hard%20disk%20partition,to%20create%20the%20Ubuntu%20partition.&text=In%20the%20partition%20pop%2Dup,the%20beginning%20of%20this%20space.)

## Understanding the Linux file system 
[Watch me](https://www.youtube.com/watch?v=HbgzrKJvDRw)

[Linux file system types](https://www.youtube.com/watch?v=V2h_Gh7vS6w) 
[Linux file system types 2](https://www.youtube.com/watch?v=_h30HBYxtws)


### Create a power point presentation that explains the different linux file systems. 

## Understanding users in Linux:

[Understanding Linux Users, Groups and Permissions](https://www.digitalocean.com/community/tutorials/an-introduction-to-linux-permissions)

[Adding Linux Users , Groups etc](https://www.youtube.com/watch?v=7d_4b7uZTtk)

[Working with Linux file permissions](https://linuxhandbook.com/linux-file-permissions/)

[Video to hlep with file permissions](https://linuxhandbook.com/linux-file-permissions/)

[working with CHMOD](https://linuxhandbook.com/chmod-command/)

### YOUR TASK ......
#### log into your linux machine and create the following folders:
1. Staff
2. HR
3. Finance
4. Top Secret Stuff
5. Who cares what is in here 
6. Shared folder 

Now creat the following users:

1. JaneHR
2. MikeStaff
3. EmilyFinancy 
4. DrWhoTopsecretstuff

NOW 
1. Make Jane the owner of the HR folder 
2. Create a group called allStaff and assign 777 permissions to the staff folder for this group 
3. Create a group called senior Managers, add Jane and Emily to this group. 
4. Give the group read only permissions to the folder. 
5. Make the root the  owner of the Top Sectret folder and apply the 400 permission
6. Create the DrWhoTopsecretstuff user - try to give himp permissions on the Topsecret folder. 
7. 









