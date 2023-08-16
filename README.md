<p align="center">
<img src="https://github.com/kura-labs-org/kuralabs_deployment_1/blob/main/Kuralogo.png">
</p>
<h1 align="center">C4_deployment-1<h1> 

## Deployment instructions :

#1. Setup Github repository: 

a. Download repository from Kura Labs C4 Deployment 1 Repo

b. Extract files via zip file downloaded from Kura Labs C4 Deployment 1 Repo
	
c. Upload files into newly made Github Repo by dragging and dropping files (because I’m using a Mac)


#2. Setup Personal Access Token w/ Github

a. Go to “Settings” and select “Developer Setting”

b. Select Personal Access Token and choose “Tokens (classic)”

c. Click “Generate new token” and select “Generate new token (classic)


#3. Setup Jenkins pipeline

a. Login using credentials

b. Build pipeline, use Github user credentials and Personal Access Token to establish connection between Jenkins & Github 

c. Run Build for successful deployment, if any issues, check the file issue within the file path or in the code itself (example: ‘import application’ may be ‘import app’ instead. 


#4. Setup IAM profile 


#5. Setup Deployment on Elastic Beanstalk and execute 

