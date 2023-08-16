<p align="center">
<img src="https://github.com/kura-labs-org/kuralabs_deployment_1/blob/main/Kuralogo.png">
</p>
<h1 align="center">C4_deployment-1<h1> 

## Deployment instructions :

a. Setup Github repository: 

1a. Download repository from Kura Labs C4 Deployment 1 Repo

1b. Extract files via zip file downloaded from Kura Labs C4 Deployment 1 Repo
	
1c. Upload files into newly made Github Repo by dragging and dropping files (because I’m using a Mac)


b. Setup Personal Access Token w/ Github

1b. Go to “Settings” and select “Developer Setting”

2b. Select Personal Access Token and choose “Tokens (classic)”

3c. Click “Generate new token” and select “Generate new token (classic)


c. Setup Jenkins pipeline

1c. Login using credentials

2c. Build pipeline, use Github user credentials and Personal Access Token to establish connection between Jenkins & Github 

3c. Run Build for successful deployment, if any issues, check the file issue within the file path or in the code itself (example: ‘import application’ may be ‘import app’ instead. 


d. Setup IAM profile 


e. Setup Deployment on Elastic Beanstalk and execute 

