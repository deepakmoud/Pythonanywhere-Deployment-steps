

#### 1. Signup
  Step 1 : login in python anywhere
  
  ![Signup](images/login_pythonanywhere.png)
**a.** Go to PythonAnywhere website at https://www.pythonanywhere.com/ and click on **Pricing & signup**.

![Signup](images/1-sign-up-1.png)

**b.** Click **Create a Beginner account** , then provide your details to get your account created.

![Provide details](images/2-sign-up-2.png)

![Provide details](images/3-sign-up-3.png)

![Provide details](images/4-sign-up-4.png)

**c.** You will see a Warning to confirm you email. Confirm your email, login again and the Warning disappears.

You will see the PythonAnywhere Dashboard giving you a summary.

![Dashboard](images/5-sign-up-5.png)

#### 2. Prepare the environment
To open the Bash console, on the Dashboard page under Consoles, under New console click **$ Bash**. This will open the bash console on the underlying linux machine.
 
 
 
 Step 2 :
Click on Recent Consoles
![Bash console](images/console.png)

![Bash console](images/6-bash-console.png)
Uploading your code to PythonAnywhere
Assuming your code is already on a code sharing site like GitHub or Bitbucket, you can just clone it from a Bash Console:



 
STEP 3:

To open the Bash console, on the Dashboard page under Consoles, under New console click **$ Bash**. This will open the bash console on the underlying linux machine.
   
![Bash console](images/6-bash-console.png)

STEP 4:
Copy your GitHub file
![GITHUB REPOSITORY](images/github.png)

STEP 5:
Write on bash git clone and past your GitHub file location
![GIT clone](images/gitclone.png)

# for example
$ git clone https://github.com/myusername/myproject.git

**a.** Many of the popular python libraries are pre-installed. You can check that by opening the Bash console.
**b.** Type the command ```pip list``` to see the pre-installed python packages and their versions.
   
![Pre-installed packages](images/6-pip-list.png)
or 
![git clone paste github reposotory link](images/6-pip-list.png)
   
STEP 6:
Go to Files section
![GO TO FILE SECTION](images/filesection.png)
    

#### 3. Create/Deploy your Web App
 
**a.** Now you can create your Webapp (The free account allows deploying a single webapp). Click on **Web**, then click **+ Add a new web app**

![Create webapp](images/10-web-app-2.png)
    
![Create webapp](images/11-web-app-3.png)
    
**b.** Select **Flask**
    
![Create webapp](images/12-web-app-4.png)
    
**c.** Then, select **Python 3.8**
    
![Create webapp](images/13-web-app-5.png)
    
**d.** You can now accept the default path and filename for the python code for flask app (I chose default), or you can provide details as per your preference.
    
![Create webapp](images/14-web-app-6.png)

You need to change path

Go to Code section and click on Source codes and rename (mysite to your GitHub file)
![change path](images/code_section.png)

NOW go to WSGI configuration file 
Write flask_app to app

![change WSGI FILE ENTRY](images/wsgi.png)

Write in project_home to your GitHub file name
![change path](images/Picture1.png)
**e.** Your web app is now deployed and active (with a default code). For the free account, to keep your web app active, you need to click the **Run until 3 months from today** atleast once before the 3 months expire.
   
Make a note of the URL for your web app (this is typically https://yourid.pythonanywhere.com)
    
![Create webapp](images/15-web-app-7.png)
    
**f.** Test the sample web app (with the default code). Open a tab in your browser and paste your web app URL
   
![Default webapp](images/16-web-app-8.png)
   


