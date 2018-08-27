# The Microsoft Graph
I often get asked, *"What is the Microsoft Graph?"* so I thought it's time to write a blog post. In a nutshell, the Microsoft Graph is a set of APIs that allows developers to access Microsoft 365 (Windows, Office and Devices) data on a user. Of course, this does require user permission and that the user is logged in using a Microsoft account (Hotmail, Outlook or Azure Active Directory).

All the end points are HTTP based and the best way to experiment with a few of them is to use the Graph Explorer:
https://developer.microsoft.com/en-us/graph/graph-explorer

The nice thing about the Graph Explorer is that you can click on the various sample queries and get a feel for the JSON data you'll get back, but if you want some real fun then authenticate by clicking this:

![Authentication](/Assets/authenticationScreen.png "Authentication")

Once you click on the show more samples link at the bottom of the samples

![ShowMoreSamples](/Assets/showMoreSamples.png "Show more samples")

And then a bunch of samples categories slide out from the right

![SamplesCategories](/Assets/sampleCategories.png "Sample categories")

I normally select a fair few of these when I'm exploring. Note that Windows features like Timeline use some of these categories like User Activities. 


