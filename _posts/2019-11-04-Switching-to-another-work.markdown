---
layout: post
title:  "Week 14.1 - Switching to another work"
date:   2019-11-04 13:33:59 +1200
categories: jekyll update
---

Today, we decided that my ticket for add tabs on Goals page is not suitable for our app.
Even I thought it was not necessary so it was easy to move on to next ticket which was 'Feature 33 - Add ring-shaped progression bar on Weekly goal tab'.

So rather than have two tabs and show edit goal part and current progress on different tabs, we decide to show them all on one screen.

For this one, I found another [good repo](https://github.com/bartgryszko/react-native-circular-progress). It will look nicer if we show user's progress on ring-shaped progression bar.

But when I tried to use it, another problem occurred. I have to figure out a 'week' that user set for 'weekly' goal.
So when user add his/her goal on our database, the app should know current date, a date after one week, goal distance, and current progress at the same time.

Once I figure that out, I automatically knew this ticket will take longer time to finish then I thought it would be.