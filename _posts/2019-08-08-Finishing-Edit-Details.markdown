---
layout: post
title:  "Week 3.2 - Finishing Edit Details"
date:   2019-08-08 13:33:59 +1200
categories: jekyll update
---

Past few days, I was working on second problem that we discussed on last class.

When a user opens this page, user needs to add all the inputs even though user already did it before.
So even if you used Edit Details before, if you want to change your information such as weight, you need to add first name and such again, to update your detail.

Flinn suggested that it would be nice to actually shows current user's information at start which was excellent idea.
But the problem was that the information of user should fill all TextInput, before page loads completely.

I couldn't figure out how to do that and kept getting errors about null instance, because our app couldn't get the data before render function.
But after few research, [this page](https://reactjs.org/docs/react-component.html) helped me to figure out how to fix that.

I used componentWillMount function from that page which will happen before render function.

![componentWillMount function](/assets/img/Week_3_2_1.JPG)

The function worked fine as it should be. Now users can see their information when they open Edit Details page.