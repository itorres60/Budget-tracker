# 19 Progressive Web Applications (PWA): Budget Tracker

Here we have a PWA for tracking a budget.  The end user puts in data regarding expenses or deposits and that data is stored in a MongoDB database.  This application is available online through the use of indexDB and service workers.

Once the user logs into the website files are then cached into the browsers cache directory.

![cache Screenshot](/screenshots/cache.png "Browser cache")

Now with the cached files functioning the webapp is able to produce those files in the browser without a connection.

The functionality of the app is also available offline through the use of indexDB.  While offline the user is able to input data and send.  This data is stored and will be triggered to post when the browser detects a connection to the internet.  

![IndexDB Screenshot](/screenshots/offline.png "Offline to online functionality")

As you can see the files failed to post, however when the connection was restored the post function was triggered and the data was sent to the server.

We used a manifest to produce the PWA functionality in order to allow for application installation onto the end users device.

![manifest Screenshot](/screenshots/manifest.png "Manifest json file")

Here we see the icon allowing for installing the app.

![install icon Screenshot](/screenshots/install.png "PWA install")



Heroke Deployed site:
[Heroku deployement](https://afternoon-island-23774.herokuapp.com/ "Here is the deployed site")