# CST8915 Lab 3: Algonquin Pet Store on Azure App Services

**Student Name**: Anoop Sidhu
**Student ID**: 040984994
**Course**: CST8915 Full-stack Cloud-native Development
**Semester**: Winter 2026

---
## Demo Video

🎥 [Watch Demo Video](https://youtu.be/z0bLI2AG7gY)

---
## Reflection Questions

1. What challenges did you encounter when configuring environment variables in the GitHub Actions workflow?
N/A, Azure Static Apps did not allow me to deploy in any region.

2. How does deploying microservices on Azure Web App Service differ from running them locally?
Azure Web App Service is PaaS, it handles launching and deploying the application (through providers) on its own, without users physically inputting commands on a VM or locally.

3. Why is it important to use environment variables for configurations in a cloud environment?
To follow the the third rule of the 12 factor principles (config). This means that everything that is different between deploys is configured in its own environment, and does not reside in the codebase.

---
## Setup Challenges

- Getting error `Resource 'Store-Front' was disallowed by Azure: This policy maintains a set of best available regions where your subscription can deploy resources. The objective of this policy is to ensure that your subscription has full access to Azure services with optimal performance. Should you need additional or different regions, contact support` when deploying to static web apps.
