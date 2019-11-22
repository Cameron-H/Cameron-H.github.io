---
layout: post
title:  "Adding Items"
date:   2019-08-12 16:32:22 +1200
categories: jekyll update
---
Now that I had Firebase configured correctly, I had to add it to our app and test it. Being guided by a tutorial, I added a text input on the second screen of the app just for testing purposes. Whatever was typed in the text box would be sent to the Firebase real time database at the click of a button. 



![](/assets/project 2/addingItem.jpg)

This function references the database directory /items and then pushes the data on field 'name' to it. This function is called in the handleSubmit function.
<br>
![](/assets/project 2/saveItem.jpg)

The handleChange function is called when a user types something else into the text box, it is called on in the onChange method. When text is changed, it sets the name variable as the current text in the box. 

The handleSubmit function calls the addItem function with the current value of name. This is called on the Add Item button.
<br>
![](/assets/project 2/addItem2.jpg)
<br>
The same concept will be used for when I work on the sign up page. 