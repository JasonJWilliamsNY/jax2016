# Introduction to Atmosphere Cloud Computing

[Atmosphere](http://www.cyverse.org/atmosphere) is one of the most versatile components of the CyVerse CI. Anything that you would normally be able to do with your local laptop/desktop, you can do on a virtual machine in the Atmosphere cloud. The advantage of using Atmosphere is that you can get access to greater resources (currently up to 16 CPU, 128GB RAM machines). Additionally, those resources are co-localized with the CyVerse Data Store so that moving to and from your instance is very easy to do. 

>**Tip:** To use Atmosphere, you must have an email address from an academic/governmental institution and request access to Atmosphere through the user portal.  To request access, login to user.iplantcollaborative.org and check to see if Atmosphere is listed under ‘My Services.’ If it is not, scroll down and click the “Request Access” button next to Atmosphere to complete a request form. 

1.	Login to Atmosphere 

### Connecting to Atmosphere instance via SSH

> **Tip:** Your Instance status must be ‘active’ in order for you to connect. Windows users can download [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html) to connect via the terminal.
2.  Open a terminal (Mac/Linux) and connect `$ ssh your_cyverse_username@cyverse.org`
3. You will be asked to save and RSA key to the list of known hosts, enter ‘yes’
4. When prompted, enter your CyVerse password.<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_4.jpg", style="width:600px;height:375px;"> 

### Connecting to Atmosphere instance via VNC

Some Atmosphere images also are configures with a desktop interface. This can be accessed using a VNC Viewer. Download VNC Viewer from Real VNC to connect to your instance. 

> **Tip:** When you download VNC viewer, the program will ask for an IP address. This IP address is available from the Atmosphere website; log into Atmosphere and locate the IP address of the instance you wish to connect to. 

1. Locate your Instance IP address (next to your instance name)<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_6.jpg", style="width:480px;height:100px;">
<img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_5.jpg", style="width:300px;height:175px;">



One of the advantages of computing within CyVerse is shared credentials and user profiles on common computing resources. This makes it easy to transfer data, and to enable collaborator access securely. In this exercise, you will share your Atmosphere desktop with another CyVerse user. 

1. Get the username of another CyVerse user and give them your IP address (from the Atmosphere website). 
2. Connect to your Atmosphere instance via VNC. 
3. In your Atmosphere instance, click the **VNC** icon in the upper right-hand corner of the Desktop; this will open a _VNC Server_ window. <br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_7.jpg", style="width:300px;height:150px;">
4. Click the **More** button on the _VNC Server_ window and select _Options..._; A _VNC Server Options_ window will open.<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_8.jpg", style="width:300px;height:350px;">
5. Select _Users & Permissions_ from the _VNC Server Options_ window, then click on **Add**.; Enter the CyVerse username of the collaborator you wish to share with; the click **OK**<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_9.jpg", style="width:300px;height:350px;">
6. Make any adjustments to the user permissions, click **Apply**, the click **OK**. Close the _VNC Server_ window. 
7. Your collaborator can now enter the IP address (+“:1”) to their VNC viewer as the server to connect to. They can connect using  their CyVerse username and their user credentials. 