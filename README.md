
## Prerequisites: 

The sample application code should be hosted on a Git repository.
You should have a DockerHub account and Docker installed on your machine.

## Step 1

Set up the repository
Create a new repository in GitHub for your sample application.
Clone the repository to your local machine.
Copy your Spring Boot application code into the repository folder.
Commit the changes and push the code to the repository.

## Step 2

Create a Dockerfile
Create a new file in the repository called "Dockerfile".

## Step 3

Create a GitHub Actions workflow
In your GitHub repository, click on the "Actions" tab.
Click on the "Set up a workflow yourself" button.


## Step 4

Configure DockerHub credentials
Go to the DockerHub website and log in to your account.
Click on your profile icon and select "Account Settings".
Click on "Security".
Click on "New Access Token" and generate a new token.
Copy the token..
## Step 5

Test the pipeline
Make a change to your code and commit it to the repository.
Go to the "Actions" tab in GitHub and check the status of the workflow.
If the workflow has completed successfully, the Docker image should be pushed to DockerHub.

## Step 6: 

Set up the pipeline Click on "Configure" for the job. Under the "Build Triggers" section, select "Build after other projects are built". Enter the name of the previous job in the "Projects to watch" section. Click on "Save" to save the pipeline configuration.

## 🔗 Links


![DockerImage](https://user-images.githubusercontent.com/70112790/228626609-dac964c5-2efb-473a-a920-6e09fb968cc4.png)

![Workflow](https://user-images.githubusercontent.com/70112790/228627712-58559e48-133e-433e-a7ef-74037f1a5283.png)
