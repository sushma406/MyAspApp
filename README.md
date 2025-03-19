# MyAspNetApp

This is a simple ASP.NET Core web application that displays a name and student ID.

## Features
- Displays the name: **Sushma Sai Kasarapu**
- Displays the student ID: **500234828**

## Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download) installed on your machine.
- [Visual Studio Code](https://code.visualstudio.com/) or any text editor.
- [Azure Account](https://azure.microsoft.com/) for deployment.

## Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/sushma406/MyAspApp.git
   cd MyAspApp
   ```

2. Restore dependencies:
   ```bash
   dotnet restore
   ```

3. Run the application:
   ```bash
   dotnet run
   ```

4. Open a browser and navigate to `http://localhost:5000` (or the URL shown in the terminal).

## Steps to Deploy to Azure
1. Create an Azure App Service:
   - Go to the [Azure Portal](https://portal.azure.com/).
   - Create a new App Service with the runtime stack set to `.NET 8 (LTS)`.

2. Deploy the application:
   - Use Visual Studio Code with the **Azure App Service** extension.
   - Right-click on the App Service in the Azure panel and select **Deploy to Web App**.

3. Verify the deployment:
   - Open the provided Azure URL in your browser.

## Continuous Deployment with GitHub Actions
1. Set up a GitHub repository and push the code.
2. Follow the [Azure GitHub Actions guide](https://learn.microsoft.com/en-us/azure/app-service/deploy-github-actions) to configure CI/CD.

## License
This project is licensed under the MIT License.
