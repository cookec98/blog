---
layout: post
title:  "Data Modeling"
date:   2021-09-24
categories: update info
author: Campbell Cooke
---

LucidChart is very easy to use and simple, while letting the user create diagrams ranging from simple to very complex. The trickiest part for me was just
fully understanding all of the cardinality relationships and how they were represented on the graphs. Because of the tools given to you, it is very easy
to represent information in a very readable and aesthetically pleasing manner, which made making the chart very fun and not too complicated. Figuring out
the exact specifics of relationships is the trickiest part of making these charts.

![Grocery Store Chart](/blog/images/Grocery Store.png)

Vertabelo on the other hand is harder to use, but the functionality of turning your schema design into database code is a huge benefit that should not be
overlooked. This lab doesn't include the SQL specific parts of this database, but even if it did, thanks to Vertabelo, there would be no issue.

![Grocery Store Database](/blog/images/Grocery Store DB.png)

There are a couple of small aspects of these models that I'm not quite confident in. I wasn't able to represent finalizing the order in these diagrams,
but also I see that as more of a permissions outside of the database problem than in the database itself. I guess I could add maybe a boolean to the
order database which if true would mean the order cant be changed anymore, but that still feels weird to me.
