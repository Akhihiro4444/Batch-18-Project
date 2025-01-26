Hosting a Static Website on Azure Storage Account

Project Overview

This project demonstrates how to host a static website using Azure Storage Accounts, an efficient and cost-effective solution for deploying static web content such as HTML, CSS, JavaScript, and images. By leveraging Azure's built-in static website hosting feature, users can create scalable and reliable websites without the need for a dedicated web server.

Problem Statement
Hosting a static website on Azure Storage is a straightforward, cost-effective solution for lightweight web applications like personal blogs, portfolios, or documentation. This guide walks you through the process of creating and deploying a static website using Azure's Storage Account service.

Project Goals
To demonstrate the setup of a static website hosting environment using Azure Storage.

To provide step-by-step guidance for deploying static content with minimal overhead.

To highlight optional enhancements, such as custom domain integration and HTTPS configuration, for a professional-grade website.

To ensure a secure, scalable, and user-friendly hosting solution for static web content.

Technologies and Azure Services Used
Technologies

HTML, CSS, JavaScript (Static website files)

Azure CLI (Optional, for command-line management)

Azure Services

Azure Storage Account:

Used to host the static website and store website files in the $web container.

Azure CDN (Optional):

To enable HTTPS and improve performance through content delivery optimization.

Azure DNS (Optional):

For integrating custom domains and managing DNS records.

Project Steps
1. Create a Storage Account.
A Storage Account serves as the foundation for hosting static websites.
    • Steps to create a Storage Account: 
        1. Open the Azure Portal and navigate to Storage Accounts.

   ![image](https://github.com/user-attachments/assets/9138bb4e-a64b-45d2-8f7b-7025b7563608)
2. Click Create to start the creation process.

 ![image](https://github.com/user-attachments/assets/648565b1-e65d-48fd-9b65-3de8d9779ec9)
3. Fill in the required details: 
    ▪ Subscription: Select the subscription under which the resource will be billed.
    


