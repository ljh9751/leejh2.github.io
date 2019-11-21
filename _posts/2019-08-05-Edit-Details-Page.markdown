---
layout: post
title:  "Week 3.1 - Edit Details Page"
date:   2019-08-05 13:33:59 +1200
categories: jekyll update
---

Today, I chose new ticket to do which was 'Feature 10. Edit Details of a user'.
First of all, I changed function called 'login' to 'editSubmit', since 'login' was just testing function for TextInputs.
Also I changed 'onPress' function of TouchableHightlight at the bottom of the page.

![Login function](/assets/img/Week_3_1_1.JPG)

![EditSubmit function](/assets/img/Week_3_1_2.JPG)

![TouchableHighlight button](/assets/img/Week_3_1_3.JPG)

After that, I tested it on actual Edit Details page.

![EditDetails page before](/assets/img/Week_3_1_4.jpg){: width="300" height="500"} ![EditDetails page after](/assets/img/Week_3_1_5.jpg){: width="300" height="500"} ![EditDetails page alert](/assets/img/Week_3_1_6.jpg){: width="300" height="500"}

Test was successful. I could see the values are updated on our database.

However, there was few problems.

First one was that our database was not planned for multiple users at this stage which cause a problem.
If there are multiple users for this app, their information should be kept individually, and current Edit Details page does not built for that, therefore it will make an error because all the database structure will be different then now.

So basically, I need to figure out a way for app to recognize 'current user' and update his/her data.

I tried to figure out this by using actual current user's ID as a table inside database, so all the users can have their own table with information about themselves.
After some research, I figured out how to acheive this. I made the editSubmit function to store data it received under current user's ID.

![Changed editSubmit function](/assets/img/Week_3_1_7.JPG)