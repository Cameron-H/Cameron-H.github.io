---
layout: post
title:  "Changing date input"
date:   2019-10-28 16:32:22 +1200
categories: jekyll update
---

As Renz and I are developing and testing the app, we notice how much of a pain it is to select your date of birth. The default Android date picker opens a calender in which you have to click back each month. This means that you would have to keep tapping this back button for a while to get to your date of birth. After doing some research, I found another date picker package on the npm website. Set up, install and linking was very simple and worked without any issues. I had to change the locale field as the date input displayed was in the wrong format. The new date picker allows the user to scroll on the date, month and year seperately without another window opening. This makes it a lot easier for the user and gives the sign up page a cleaner look.
<br>


Old date picker, the default android one. Looks good and works well, however a pain to use when selecting your date of birth.
<br>
![](/assets/project 2/dateOld.JPG)
<br>
New date picker that allows the user to scroll through the different dates without opening a window.
<br>
![](/assets/project 2/dateNew.JPG)
<br>
The old date picker had lots of options which weren't needed with the new one. The syntax for everything else is the same. 
<br>
![](/assets/project 2/datePickerCode.JPG)