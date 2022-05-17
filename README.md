Industry Name : Ed-Tech .
Project tilte : OnlineSurveyForm
Summary : Creating a survey form that allows the user to select his preferences from favorite features of freeCodeCamp which includes challenges, projects, community, Opensource.
Synopsis : Creating a survey form that allows the user to select his preferences from favorite features of freeCodeCamp which includes challenges, projects, community, Opensource.
Azure sevices used : Microsoft Azure portal.

The deployment procedure is as follows:
1.Login into azure portal using credentials.
2.Clink on a storage account.
3.Create a new storage account.
4.Select the subscription and resources
Name the storage account as "OnlineSurveyForm"
5.Click on create and review
6.Once validation is successful, click on create.
7.Storage account is created.
8.Launch Visual Studio Code.
On the toolbar, click Extensions. Search for Azure Storage, and select the Azure Storage extension from the list.
Then click the "Install" button to install the extension.
9.Open the Azure portal in your web browser.
Locate your storage account and display the account overview.
10.Select Static website to display the configuration page for static websites.
11.Select Enabled to enable static website hosting for the storage account.
12.In the Index document name field, specify a default index page of index.html.
13.In the Error document path field, specify a default error page of 404.html
14.Click Save. The Azure portal now displays your static website endpoint.
15.In visual studio code open the folder containing project details ie index.html, error.html , images.
16.Right-click under the folder in the Explorer panel and select "Deploy to Static Website via Azure storage" to deploy your website. You will be prompted to log in to Azure to retrieve a list of subscriptions.
17.Select the subscription containing the storage account for which you enabled static website hosting. Next, select the storage account when prompted.
18.Visual Studio Code will now upload your files to your web endpoint, and show the success status bar. Launch the website to view it in Azure.

The deployement of a static website to Azure is successfully completed.

