Hello! Here's a guide on how to: one) download VSCode; two) remotely connect; three) try some commands

Step 1: Downloading VSCode

Follow this link below:
https://code.visualstudio.com

![Image](image1.png)

Follow the instructions on screen and download the option best suited for you computer/software!

Once dowloaded, your screen should look something similar to the following picture. 

![Image](image2.png)

Step 2: Remotely Connecting

Open a java terminal in VSCode which can be done by opening a new java file, selecting Terminal command at the top of your screen, and seeing a terminal like the one pictured below:

![Image](image3.png)
![Image](image4.png)
![Image](image5.png)

Next to the % sign type the following - ssh cs15lsp23zz@ieng6.ucsd.edu - where zz is the unique characters assigned to your CSE15L account.

![Image](image6.png)

!!!! I WAS HAVING TROUBLE LOGGING IN AT THE TIME SO THIS IS THE SCREENSHOT I CAN PROVIDE RIGHT NOW !!!!!

Considering this is the first time you will be logging in you may get a message similar to:

The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 

You should say YES to tha above message!

You will then be prompted to enter your password for the account cs15lsp23zz@ieng6.ucsd.edu! Enter you password of course!

If not prompted for the password again, you should be now remotely connected as see something similar to:


Hello cs15lsp23zz, you are currently logged into ieng6-203.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   17:50:01   32  0.09,  0.32,  0.37
ieng6-202   17:50:01   30  0.08,  0.26,  0.35
ieng6-203   17:50:01   33  0.32,  0.58,  0.57

 
Wed Apr 05, 2023  5:52pm - Prepping cs15lsp23



Step 3: Trying Commands

To try commands you will see something simlar to:

![Image](image7.png)

After the $ sign, type a command and press enter! You will either see something like what's pictured above or it will ask for another command because the previous one was invalid!

And there you go you have downloaded VSC, connected remotely, and ran a command for the first time! Hope this helped!

