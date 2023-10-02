# mysql_cloudmanaged_databases

# MySQL Cloud Managed Databases

**Homework Assignment #4:** Explore MySQL and its implementation on leading cloud platforms: Azure and GCP.

## Summary of the Assignment

This assignment focuses on setting up MySQL instances on Azure and GCP, using MySQL Workbench to interact with databases, and documenting the process.

### 1. Azure
- Log in to your Microsoft Azure account.
- Search for "Azure Database for MySQL" and click "Create."
- Follow these steps:
  - Basics:
    - Create a resource group and instance name.
    - Choose the "for development or hobby projects" option.
    - Select "Burstable" for compute and "B1MS" for storage.
  - Authentication:
    - Create a username and password.
  - Networking:
    - Enable public access and configure firewall rules.
- Click "Create Instance."

### 2. GCP
- Log in to your Google Cloud account.
- Create a new project.
- Enable the SQL API.
- Follow these steps:
  - Instance info:
    - Set instance ID and password.
  - Choose a Cloud SQL edition:
    - Select "Enterprise" and "Sandbox."
  - Customize your instance:
    - Choose "Shared core" with 1 vCPU and 0.614 GB RAM.
    - Configure network settings to allow all IP addresses.
- Click "Create Instance."

### 3. MySQL Workbench
- Use the provided SQL code to create tables.

## Reflections on the Assignment

### GCP and Azure Setup
- Followed Professor Hants' instructions from class.
- Created a project, enabled the SQL API, and configured the instance.
- Set up public access for convenience.
-configured firewall rules.

### MySQL Workbench Experience
- Positive overall experience.
- No issues creating tables or running commands.
- Found it user-friendly and well-organized.
- Minor inconvenience: Needed to restart for each connection.

### ERD Creation
- Generated ERDs for both GCP and Azure.
- Found it simple and straightforward.
- ERDs were informative and interesting to analyze.

## Documentation of Errors
- No major errors encountered.
- Thoroughly documented any challenges faced.
- Included screenshots and descriptions for reference.
