# 100 Days Of Code - Log

### Day 4: Feb 01, 2021
1. Today covered AWS Amplify instead of Python
2. Followed tutorial to publish React app with Github repo:
https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/module-one/?e=gs2020&p=build-a-react-app-intro
https://master.d1073yy4pj9rd3.amplifyapp.com/

2a) Created React App Locally
-----------------------
npx create-react-app amplifyapp
cd amplifyapp
npm start

2b) Created GitHub repo and push the code
https://github.com/ankurkumarz/awsamplifypoc

2c) Configure & Deploy App with AWS Amplify using AWS Console. Also connect with GitHub

2d) Install & Configure AWS Amplify
npm install -g @aws-amplify/cli
amplify configure

2e) Setup IAM user and provided Amplify Admin access: AdministratorAccess-Amplify

2f) Created Amplify Backend app

2g) Setup Amplify Backend app locally:
amplify pull --appId d3rx893zmp6kh9 --envName staging
amplify console

2h) Add Authentication
npm install aws-amplify @aws-amplify/ui-react
amplify add auth
amplify push --y

The storage category enables you to create and manage cloud-connected file & data storage. App content (images, audio, video etc.) can be in an public, protected or private storage bucket powered by Amazon S3. App data is stored in a NoSQL database backed by Amazon DynamoDB and can be accessed with a REST API and Lambda function.
Amplify Authentication provides a backend authentication service with Amazon Cognito, frontend libraries, and a drop-in Authenticator UI component. Authentication is a process to validate who you are - features include user sign up, user sign in, multi-factor authentication, user sign-out, and passwordless sign-in. You can also authenticate users by integrating with federated identity providers such as Amazon, Google, and Facebook. Amplify Authentication integrates seamlessly with other Amplify categories such as API, analytics, and storage so you can define authorization rules for unauthenticated and authenticated users.


### Day 3: Jan 28, 2021
1. Covered Python Basics from https://www.w3schools.com/python/ up to Loops
Few interesting things of Python:
 a. For loop's incremental approach: for x in range(2, 30, 3): #increment by 3
 b. List, Tuple, Dictionary & Set: Tuple concept is different from langs
 c. Terminary operator of If

### Day 2: Jan 26, 2021
**Today's Progress**: 
1. Configured ipykernel in VS Code for running Jupyter notebooks
https://code.visualstudio.com/docs/python/jupyter-support-py

2. Refreshed Python for Data Types

### Day 1: Jan 25, 2021
**Today's Progress**: 
1. Started refreshing Python 
2. Setup VS with Python (though had PyCharm)
3. Setup Conda to support environemtns: 
conda create --name dev
conda list env
conda activate dev
conda install -n dev pip
4. Activate Conda Environment in VS Code
Ctrl+Shift+P -> Python: Select Interpreter -> Select Virtual Env
5. Installed matplotlib
Terminal: Create New Integrated Terminal -> To Activate Dev Env & Install 
python -m pip install matplotlib
5. Debugged Sample Code using matplotlib
6. Followed steps from here: https://code.visualstudio.com/docs/python/python-tutorial 
https://code.visualstudio.com/docs/python/environments

### Day 0: Jan 23, 2021

**Today's Progress**: Started Python Course

**Thoughts:** Initial Switching from Java to Python has some challenges as the habit of using Java keywords and syntax is hard to unlearn.