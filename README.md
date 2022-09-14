# Take a Break Reminder App

[![Take-a-Break-Reminder-App.gif](https://i.postimg.cc/brTVktZj/Take-a-Break-Reminder-App.gif)](https://postimg.cc/fSVvhk7H)

Take a break Reminder is an application that aims to remind you of the importance of taking time to do what you want to take a break from your work schedule!
Our main goal is teach you how to develop an application using Microsoft Graph JavaScript SDK integrated with Microsoft Teams and Alexa!

## 🚀 Resources Used

* **[Visual Studio Code](https://code.visualstudio.com/)**
* **[Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/download-app?rtc=2)**
* **[Microsoft 365 Developer Program](https://developer.microsoft.com/en-us/microsoft-365/dev-program)**
- **[Azure Functions Core Tools 4.x](https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Cwindows%2Ccsharp%2Cportal%2Cbash)**
* **[Microsoft Graph](https://developer.microsoft.com/en-us/graph)**
    * **[Microsoft Graph JavaScript SDK](https://github.com/microsoftgraph/msgraph-sdk-javascript)**
* **[Node.Js 16.x](https://nodejs.org/en/)**
* **[Alexa JavaScript API](https://developer.amazon.com/en-US/docs/alexa/web-api-for-games/alexa-javascript-api.html)**

## 🔥 How to run the application locally?

1. First go to the folder: `demo -> reminder-app` and run the command:

```bash
npm install
```

2. Now create a file called: `local.settings.json` (root of the project) and include this information below:

```js
{
  "IsEncrypted": false,
  "Values": {
    "FUNCTIONS_WORKER_RUNTIME": "node",
    "AzureWebJobsStorage": ""
  },
  "Host": {
    "LocalHttpPort": 7071,
    "CORS": "*"
  }
}
```

3. Now you can execute the command:

```bash
npm run dev
```

*under construction*

## ⭐️ Important Resources

- ✅ **[Microsoft Graph Documentation](https://docs.microsoft.com/en-us/graph/)**
- ✅ **[Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer)**
- ✅ **[Free Courses - Microsoft Graph](https://docs.microsoft.com/en-us/training/browse/?products=ms-graph&resource_type=learning%20path)**
- ✅ **[Microsoft Graph JavaScript SDK](https://github.com/microsoftgraph/msgraph-sdk-javascript)**
- ✅ **[Azure Functions Documentation](https://docs.microsoft.com/en-us/azure/azure-functions/)**
- ✅ **[Free Courses - Azure Functions](https://docs.microsoft.com/en-us/training/browse/?products=azure-functions)**

## ❓ Questions? Comments? 

If you have any questions about the code developed, feel free to open an **[ISSUE HERE](https://github.com/glaucia86/take-break-reminder-app/issues)**. We'll get back to you soon!
