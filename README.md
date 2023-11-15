# AzDevops_React_Webapp

DEPLOYING REACT APP TO AZURE WEBAPP SERVICE AUTOMATED WITH AZURE DEVOPS PIPELINE

![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/76952aa0-9705-4924-84e5-1d24699783a0)



## Project Structure

- **src/:** Contains the source code of the React application.
- **public/:** Houses static assets and the main HTML file.
- **azure-pipelines.yml:** Configuration file for Azure DevOps CI/CD pipeline.


# Technology Stack

This project utilizes the following technologies and tools:

- **Frontend:**
  - [React](https://reactjs.org/): A JavaScript library for building user interfaces.
  - [Create React App](https://create-react-app.dev/): A tool to set up a new React project with a single command.
  
- **Build and Package Management:**
  - [npm](https://www.npmjs.com/): The package manager for JavaScript.
  
- **Continuous Integration/Continuous Deployment (CI/CD):**
  - [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/): CI/CD platform for automating the build, test, and deployment phases.

- **Source Control:**
  - [Git](https://git-scm.com/): Distributed version control system.
  - [Azure Repos] - for hosting

- **Cloud Services:**
  - [Azure App Service](https://azure.microsoft.com/en-us/services/app-service/): A fully managed platform for building, deploying, and scaling web apps.
  - [Azure Active Directory](https://azure.microsoft.com/en-us/services/active-directory/): Identity and access management services.

- **Testing:**
  - [Jest](https://jestjs.io/): A JavaScript testing framework.

- **Documentation:**
  - [Markdown](https://www.markdownguide.org/): Lightweight markup language for creating formatted text.

- **Version Control:**
  - [GitHub](https://github.com/): Web-based hosting service for version control using Git.

 

## Key Features

- **Continuous Integration (CI):**
  - Npm install, build, and test stages., Generate .Zip.,
  - Automated artifact publishing.

- **Continuous Deployment (CD):**
  - Deployment to Azure App Service.
  - Secure integration with Azure Active Directory for service principal secrets.

## Getting Started

1. **Clone the repository:**
2. **Install dependencies:**
3. **Run the application locally:**


## CI/CD Pipeline

The CI/CD pipeline is configured in the `azure-pipelines.yml` file. It consists of the following stages:

- **Build (CI):**
- Npm install
- Npm build
- Npm test
- Publish artifacts

- **Release (CD):**
- Deploy to Azure App Service

## Azure Resources

- **Azure Repos
- **Azure App Service

## Deployment Process

1. Commits to the `main` branch trigger the CI pipeline.
2. Successful CI builds trigger the CD pipeline for deployment to Azure App Service.

## Azure DevOps Configuration

- **Service Connection:** Connected to Azure Resource Manager.
- **App Registration:** Azure Active Directory for secure service principal secrets.
- **Agent:** Self-hosted agent for customized pipeline runtime.



Setting and cloning initial project setup
 
![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/fb240029-ef66-4e93-a36a-0974f5c31117)

Initializing React app
 

 ![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/069b6fe5-48bf-42ce-b2be-2398ff56a155)



 
![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/96b178cb-2ede-4e20-ae70-94af3b15ad86)

![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/7892f30c-fd6b-4e1a-925f-0107f6ecea89)


 ![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/a9604e2a-264a-4611-8776-59a6a73e2cf4)


Stage and push the code to azure repo ( git ) 
 ![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/543b1a63-b590-4075-931e-3f97a4639a88)


Also to setup the app service in Azure
 ![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/0d6cabe0-710e-474c-bc7e-8dc6062a1833)

![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/c4e8ddce-a8a3-4e02-ab38-0ea5fe1071c3)

 


Setup the CI
![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/e293ca8a-3b93-4db2-8955-7bcaa3ecf886)

 

Setup continuous integration trigger

 ![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/0177f76a-18ad-4b53-9f01-46928c594343)


Setup the self hosted agent and run the CI
 ![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/8786d4a0-4a89-4e44-a23d-03b87240d4f6)

Monitor the build process
 
![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/2ffa79d4-be13-4f45-806b-f121c04f2c2d)

 
![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/f4b4a5db-5c95-4b06-9909-fc1347878574)

Setting the release pipeline

To:

 ![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/d3a6cb25-295f-4f4f-9369-fd1e1ec9ec33)

![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/082959d3-2697-42a5-869c-7476d5b551d5)

 
 

Appservice -webapp verification
 
![image](https://github.com/thulasigithub123/AzDevops_React_Webapp/assets/87015668/579ed9ed-86ff-429e-a6c1-c3d9818f13b2)

 
