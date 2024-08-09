# Cloud_DevOps_Engineer_Assignment
Task: Implement a CI/CD Pipeline with GitHub Actions for Automated Deployment and Rollback

Problem Statement: Configure a GitHub Actions workflow to automate the deployment of simple web application on github to AWS ECS (Elastic Container Service). 

The pipeline should include deployment, integration tests, and rollback functionality. With following steps.

Step1:Setting Up a GitHub Repo
=
<html>
<body>

<h2>Github Repository </h2>
<img src="https://github.com/user-attachments/assets/aba98775-8420-4385-94eb-e5f65c2a212b" alt="Github Code Repository No:1" width="800" height="300">
<img src="https://github.com/user-attachments/assets/12cdb578-63d8-45ba-a1c6-c5d4100017e3" alt="Github Code Repository No:2" width="800" height="400">
</body>
</html>



Step2:Creating a Multistage Docker File to serve with nginx as reverse proxy
=
<html>
<body>

<h2>DockerFile </h2>
<img src="https://github.com/user-attachments/assets/2dd1093f-05c8-4f68-8413-a24729f29e2d" alt="DockerFile" width="800" height="300">

</body>
</html>




Step3:Push image to ECR
=
<html>
<body>

<h2>ECR Repository on AWS </h2>
<img src="https://github.com/user-attachments/assets/970f7144-fbfc-498c-b964-d76d7b921931" alt="Setting up ECR on AWS" width="800" height="300">
<img src="https://github.com/user-attachments/assets/bfd9761a-48de-4015-86c7-8c988497bc08" alt="ECR Repositories on AWS" width="800" height="300">
<img src="https://github.com/user-attachments/assets/6b2c6533-d926-4036-84eb-aa9f6dcf13a8" alt="Image Details on ECR Repositories on aws" width="800" height="400">
<img src="" alt="Multistage DockerFile With Nginx Reverse Proxy" width="800" height="400">
</body>
</html>

CICD pipeline to Deploy Docker Image on ECR Repository on AWS via Github Actions:
=

<html>
<body>

<h2>CICD Through GitHub Actions </h2>
<img src="https://github.com/user-attachments/assets/e116ce10-f0d4-4b5b-865a-60465931796f" alt="Workflow file to Deploy on ECR yml file " width="800" height="300">
<img src="https://github.com/user-attachments/assets/3f6a4166-4be1-4e52-903c-4058ec435fb1" alt="Actions" width="800" height="400">
<img src="https://github.com/user-attachments/assets/82222f84-ad59-4630-ac03-4bada1a733e1" alt="Actions Summary" width="800" height="400">
<img src="https://github.com/user-attachments/assets/93bd65db-5d25-4237-a7f6-a247cffbd7c7" alt="Steps of Github Actions Workflow File " width="800" height="400">
</body>
</html>
