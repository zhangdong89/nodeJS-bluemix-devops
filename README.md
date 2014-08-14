nodeJS-bluemix-devops
=====================

This is a sample node.js application, I am using this application to show how to deploy and update node application from JazzHub by Web IDE. Please follow the step by step if you have intrested.

=====================
What you need?
=====================
1. Bluemix ID https://ace.ng.bluemix.net
2. Jazz ID, and bind with your Bluemix ID https://hub.jazz.net/

=====================
Step by Step to deploy application to Bluemix from Web IDE
====================
1. Access https://hub.jazz.net/project/arzetry/nodeJS-bluemix/overview to get sample code from IBM JazzHub site.
2. Click "Edit Code" 

![image](https://raw.githubusercontent.com/acostry/nodeJS-bluemix-devops/master/nodeJS-bluemix/pics/editcode.png)

3. Click "FORK" to fork sample application to your own Jazz repository.

![image](https://raw.githubusercontent.com/acostry/nodeJS-bluemix-devops/master/nodeJS-bluemix/pics/fork.png)

4. Go into your own repository, click "Deploy AS" to select deploy application to Bluemix, you need to set the Org/Space for the applcation, wait a min, you will see the successful massage about deployment.

![image](https://raw.githubusercontent.com/acostry/nodeJS-bluemix-devops/master/nodeJS-bluemix/pics/deployas.png)

====================
Update application from Web IDE and re-deploy the change to Bluemix
====================
1. See below picture, modify "Hi world" to "Hi Bluemix"

![image](https://raw.githubusercontent.com/acostry/nodeJS-bluemix-devops/master/nodeJS-bluemix/pics/update.png)

2. Click "Deploy" to deploy the updated version to Bluemix.
3. Access your application and you can see the changes from the home page.

The application URL should be http://app_name.mybluemix.net
