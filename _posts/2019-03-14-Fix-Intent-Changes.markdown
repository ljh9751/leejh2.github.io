---
layout: post
title:  "Week 4.1 - Fix intent changes"
date:   2019-03-14 13:00:00 +1200
categories: jekyll update
---
1. Joon finished working on "Splash screen redirect to login page"

Even though we still not sure about how to use fork or can we use branch, I just kept working on my task as Flinn did on his. After I heard about his login page and its name, I modified "SplashScreen.java".

![March_14_1](/assets/img/March_14_1.JPG)

So what these codes suggests are, if someone opened application and has no user id that is stored in the device (we have no clue how to work with database yet), splash screen will redirect the user to "Login" page which has "sign up". However, if someone already used this, splash screen will redirect the user to "WalkingActivity", which makes that user to start walking right away.<br>

This is not a complete version because after we learn about using database internally and externally from the device, we need to fix this order.<br>

In the end, "Splash" screen will lead the user to "Log in" page and then user can decide logging in with signed up account or create new account by go to 'Sign up' page.