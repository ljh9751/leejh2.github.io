---
layout: post
title:  "Week 4.1 - Clear Data page"
date:   2019-08-12 13:33:59 +1200
categories: jekyll update
---

Today, I chose new ticket, to create a Clear Data page.

I wasn't really sure what Clear Data page do but since it was there on original app, from last project group, I tried to work it out.
So to start with, I created simple page with a button to wipe out user's detail, since I though it was what 'data' from Clear Data means.
I made all data related to user's detail into null so basically it is empty.

![Clear Data page](/assets/img/Week_4_1_1.png)
![ShowAlertDialog function](/assets/img/Week_4_1_2.png)

I also added two alerts so user need to be sure to clear their user details.

![Clear Data page with first alert](/assets/img/Week_4_1_3.png)
![Clear Data page with second alert](/assets/img/Week_4_1_4.png)

The result was not good.

![Clear Data page with few data left](/assets/img/Week_4_1_5.png)

Some data were not cleared as some of them are used on authentication.
Also sometimes I received an error from Google Firebase because I made all the data null but still tried to pull the data from Firebase every time I reload the page
(I made the page to do that from last ticket)

I need to think more carefully about this.