
![azure web app](https://github.com/Skizfly/AzureAppService/assets/153954157/ead9bf92-5ee7-4b62-bfec-81940b3e213a)


<h1>Deploy Web Application to Azure Web App (Azure)</h1>
Welcome to my tutorial on deploying a web app to Azure. I will illustrate the process of getting your application up and running on the Azure platform using Visual Studio.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Visual Studio
- PowerShell

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Advanced Deployment and Configuration Steps</h2>

- Create Web App in Azure
- Create Web app framework 
- Connect deployment source 
- Deploy created app to Azure
- Test web app url in Azure

<h2>Azure Configuration Steps</h2>

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/5708955e-78a2-4122-8509-affbf07fc76c)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/125f333e-d04b-4171-8c27-87375e20c5e9)

<p>
</p>
<p>
Before embarking on the setup, it's prudent to initiate a resource group for meticulous organization. Once that's established, proceed to the quest for "app services" in your Azure environment.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/757cb988-1f6d-4c85-86b0-bd0e6aa11f90)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/42e75c20-af3f-4d43-acf2-9db274d9dc53)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/0c2fc232-7fdd-4cbb-a516-b29e46893ca2)


<p>
</p>
<p>
Upon reaching the "App Services" section, click on the "Create" button, then select "Web App" from the dropdown menu (take note of other options and choose accordingly for your project). Assign a distinctive name to your app and configure the settings as per your requirements. Once done, proceed by clicking on "Review" and then "Create." Now, patiently wait for the deployment to complete and watch for the confirmation message.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/4724e9ad-4e96-40c8-abba-66c2ae2b0f79)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/70739391-b5ed-4062-aebf-1d3d6efa1624)


<p>
</p>
<p>
Upon successful deployment, access the resource and observe the generated URL for your Azure web app. Execute a click on the link, initiating a new window. At this juncture, Azure eagerly awaits the coding input from your developed web application. Now, let's seamlessly transition to the subsequent phase of linking the two entities.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/559a54d1-215b-4140-8880-5f0f02c1c1d3)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/e52cf7d2-f170-4d75-b045-97223c236e2d)

<p>
</p>
<p>
If you haven't done this yet, make sure to download Visual Studio from Microsoft; it's a free program. This is the tool we'll use to develop and deploy our web app to Azure. Additionally, before we kick off, it's crucial to create a new folder on your desktop or any easily accessible location – this will serve as the container for your web app files.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/a18d00f1-aac5-4e6f-9824-4c09828356d6)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/1eb36237-4ad7-4ef7-b841-bc8eaf2450c6)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/ade5430d-b5dc-4eaf-9a91-f72af7312631)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/8bf378a1-806d-4b47-af07-15b29a26ef02)


<p>
</p>
<p>
With Visual Studio now active, begin by initiating a new project. Opt for the ASP.NET Core web app template in the next step. Proceed to configure your project details, ensuring you save it in the previously created folder. In the final steps, adjust any additional settings and then press the "Create" button.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/834941e7-4bb1-4096-90fd-f06d61e442d3)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/665e7733-7cac-453c-9adb-3639be06e93a)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/f7a4145b-c7ec-43fa-9921-24fae1534113)


<p>
</p>
<p>
With our project now created, your screen should resemble the configuration in the first screenshot above, showcasing some pre-built framework. For the purposes of this demonstration, let's assume we've already constructed our web app. Now, let's open PowerShell and execute the command: `dotnet run`. This command initiates the construction of the app framework. Upon completion, a webpage will appear, displaying your web application. Once this step is accomplished, we can seamlessly progress to the deployment phase on Azure.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/d592f58a-476b-4b0e-96c1-3b2dba3eabe4)

<p>
</p>
<p>
Let's initiate the deployment to Azure. Navigate to the Solution Explorer, right-click on your web app's name, and choose the "Publish" option.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/093a0ebc-234b-4688-8ae9-dd5c31616edb)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/fbf50dda-aea0-48fe-ab81-4b7b4e3bbbd9)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/f4d26f00-c7c4-4d18-b042-297d43bb3e62)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/dc38bade-05d1-4819-a82d-d424879af452)
![image](https://github.com/Skizfly/AzureAppService/assets/153954157/541a55d8-fcef-4590-913f-8cb87539b9c1)

<p>
</p>
<p>
Let's follow a series of steps to guarantee a successful deployment to Azure:

1. Choose the Azure option as your publish location.
2. Select your Azure service.
3. Since we've created a web app in Azure earlier, log in to your Azure account (located at the top-right corner). Once logged in, navigate through your resource group to select the specific web app you've created.
4. Click "Finish," and Visual Studio will initiate the deployment process.
5. Once you see the "Ready to Publish" message, proceed and click the "Publish" button.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/97ccb735-feef-44a6-877a-d34509bb73e7)

<p>
</p>
<p>
Upon completion of the publishing process, a new window will emerge. Take note of the updated URL, such as filefeeder.azurewebsites.net (replace it with your unique web address). To confirm, let's head back to our Azure portal and verify the changes.
</p>
<br />

![image](https://github.com/Skizfly/AzureAppService/assets/153954157/d70a1831-65d8-44c6-87e4-f02439ec3b62)


<p>
</p>
<p>
Within the Azure portal, navigate through your resource group to locate your Azure web app. Open the resource, find the default domain name, and click on the link. Your created web app should then appear in a new window within the Azure environment.
</p>
<br />
<h2>A Conclusion</h2>
In this tutorial, we embarked on a journey to deploy a web app to Azure, covering key steps and considerations. We started by creating a resource group for organization, explored the setup of Azure Web App, and integrated it with Visual Studio. The development process included crafting the app, initiating it with PowerShell, and viewing the results locally. Transitioning to Azure, we navigated through essential deployment steps, ensuring seamless integration with our Azure resources. Lastly, we verified the deployment's success by checking the updated URL in the Azure portal. Through this journey, we gained insights into deploying, managing, and monitoring web apps on the Azure platform.
