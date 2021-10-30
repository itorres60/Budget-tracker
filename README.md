# 19 Progressive Web Applications (PWA): Budget Tracker

Here we have a PWA for tracking a budget.  The end user puts in data regarding expenses or deposits and that data is stored in a MongoDB database.  This application is available online through the use of indexDB and service workers.

Once the user logs into the website files are then cached into the browsers cache directory.

![cache Screenshot](/screenshots/cache.png "Browser cache")

Now with the cached files functioning the webapp is able to produce those files in the browser without a connection.

The functionality of the app is also available offline through the use of indexDB.  While offline the user is able to input data and send.  This data is stored and will be triggered to post when the browser detects a connection to the internet.  

![IndexDB Screenshot](/screenshots/offline.png "Offline to online functionality")


https://afternoon-island-23774.herokuapp.com/
[Social Network API demonstration video](https://drive.google.com/file/d/1UDA8c_uWnxB3AgwOyTqgrpv69PijCsm6/view?usp=sharing "Social Network API demonstration video-disco")