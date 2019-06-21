---
layout: post
title:  "Working on the backend"
date:   2019-04-12 16:32:22 +1200
categories: jekyll update
---
A person frome the DevOPS team came through with a prompt reply including the details for a new server that I can use.

I started working on it during the mid semester break. The web and database server is going to be used for holding user information for testing. We don't know what the current server situation that Enabling Love has got. So we can keep moving forward, the team and I thought it would be a good idea to set up a local server just for testing purposes.

Both web and database servers will be held on the same sever. This is usually not what you'd do but for local testing, this is fine. The web server uses a module called Flask and the database server is using MongoDB. The web interface and the database are communicating using mongoengine. 

I added a route that would just return the data stored in the DB (Username, latitude, longitude) to a JSON format which will then be then parsed in the Android app itself.

![](/assets/ev8.JPG)

<br>

![](/assets/ev9.JPG)








