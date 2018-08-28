# Supercharge your experiences with the Microsoft Graph

## Framing: What is Microsoft 365?
M365 is a term you'll be hearing more frequently from Microsoft, but for a developer, what does this really mean? In this post I'll show you how you can supercharge your Windows/Cross Platform/Web experience to utilize the vast array of M365 services from Email, Calendar, Excel and Insights.

The first question I often get asked is: *"What is M365?"*

In a nutshell, M365 is a solution including:
* Office 365
* Windows 10
* EMS (Enterprise Mobility and Security)

If you'd like more details on Microsoft 365, checkout:
https://www.microsoft.com/en-us/microsoft-365


## Microsoft Graph
Tying together the 3 pillars of Microsoft 365 is the Microsoft Graph. 

![Microsoft Graph](/Assets/microsoft_graph.png)

The Microsoft Graph is a set of HTTP endpoints that allows developers to access Microsoft 365 data:
* Azure Active Directory
* Office 365 services: SharePoint, OneDrive, Outlook/Exchange, Microsoft Teams, OneNote, Planner, and Excel
* Enterprise Mobility and Security services: Identity Manager, Intune, Advanced Threat Analytics, and Advanced Threat Protection.
* Windows 10 services: activities and devices

*Note: This does require permission and that the user is logged in using a Microsoft account (Hotmail, Outlook or Azure Active Directory)*

### Microsoft Graph Explorer 
Now you know what the Microsoft Graph is, and it's relation to Microsoft 365. What can you do with it? The best place to get a deeper undstanding is [Microsoft Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer) (https://developer.microsoft.com/en-us/graph/graph-explorer). This web site shows you just some of HTTP calls you can make to supercharge your experience.

The nice thing about the Graph Explorer is that you can click on the various sample queries and get a feel for the JSON data you'll get back: 
![GraphWebsite](/Assets/graphWebsite.png "Graph Website")

If you want some real fun, then authenticate using your credentials by clicking this:

![Authentication](/Assets/authenticationScreen.png "Authentication")

Once authenticated, you'll be able to use the POST methods too. Be careful though, remember this is a live POST using your account!

 If you want some more endpoints, like Teams, OneNote, Outlook, Insights, People etc. Click on the **show more samples** link at the bottom of the samples

![ShowMoreSamples](/Assets/showMoreSamples.png "Show more samples")

And then a bunch of sample categories slide out from the right

![SamplesCategories](/Assets/sampleCategories.png "Sample categories")

I normally select a few of these when I'm exploring. You might even recognize some of the data that Windows uses, for example features such Windows Timeline and Continue on PC all use the Microsoft Graph in someway.

My favourite is *find meeting time*:

![FindTime](/Assets/findTime.png "Find time")

This removes a big pain when I'm trying to organize a meeting with a lot of people.

### Windows Community Toolkit
Another great resource to get you up and running is the [Windows Community Toolkit](https://aka.ms/windowstoolkit
). I won't go into details about the toolkit here (it's a whole new blog post!) but I want to call it out because it has some Graph controls which are super handy, like connecting to AAD.

![WindowsCommunityToolkit](/Assets/toolkit.png " Graph Controls")

I hope you enjoyed this brief overview of the Microsoft Graph and I encourage you to try it. It's super simple to play with thanks to the tools mentioned in this post.  To learn more about the Microsoft Graph, check out our great docs:
https://developer.microsoft.com/en-us/graph/docs/concepts/overview
