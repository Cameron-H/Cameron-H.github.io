---
layout: post
title:  "Age and Gender"
date:   2019-09-10 16:32:22 +1200
categories: jekyll update
---
Age and gender fields will also be needed for the swiping part of the app to work. I have added two more inputs to the sign up page. Date of birth is selected by using the DatePicker input, this brings up a calender box on Android and a scroll selector on iOS. Gender is selected using two radio buttons. The date is converted to a string and then sent to the real time database. When the user goes onto the second screen (test screen), it will pull the date from Firebase and then using an age calculator function, the age will be then worked out. This will be a variable that will be used to filter age when we have implented the swiping functionality.

<br>
![](/assets/project 2/locationDOB.JPG)

This shows how I implented the radio buttons for gender. I centered them, kept them blue and kept the default size as it stands out and makes it easier for the user to pick what gender they are.
<br>
![](/assets/project 2/signupUI.JPG)

Once a date has been selected and the sign up button has been pressed, the date is sent to Firebase and stored in the following format. Even though it's the US format, it's necessary to have that so that the age calculator function can work properly. 
<br>
![](/assets/project 2/dobFirebase.JPG)

