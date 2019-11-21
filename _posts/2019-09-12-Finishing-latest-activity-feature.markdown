---
layout: post
title:  "Week 8.2 - Finishing latest activity feature"
date:   2019-09-12 13:33:59 +1200
categories: jekyll update
---

Today, I finished my light tickets, including showing latest activity of a user.

I googled about querying Firebase database and found out about limitToLast function.
If you pass some number into that function, the database will send only number of record from bottom end to top.
So if I pass 1 to that function, the data I receive will be the latest activity since every data ordered by its date, past to present.

![lastResult function](/assets/img/Week_8_2_1.JPG)

I used lastResult function and be able to obtain one data that shows latest activity.

This work became a ticket called 'Feature 18 - Display previous walk/run activities', therefore I finished about three tickets.
It was good experience because this work made me realize that I don't know about using Google Firebase then I thought I did.

I should study more about querying Firebase database for future usage.