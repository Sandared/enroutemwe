---
layout: news
title: Concurrency App Note by SMA
author: Jane Doe
published_at: 2017-09-22
---

In OSGi you will write code that runs in a multi-threaded environment. There are no safe guards, no hand-rails, and no warning signs. When you register a service anybody can call you at any moment in time. In multi-core CPUs (are there any others?) your code can execute multiple times in any given instant. There will be dragons here.
Except for a few sissy Java EE App servers, this is the standard way of working for Java. Get over it, accept it! You must consider the concurrency issues of your code. For this, there are some excellent books out there that explain the issues. The most famous one being Brian Goetz’ book Java Concurrency in Practice, the bullet train book.
This App note attempts to handle some of the important issues when you write OSGi applications, especially with DS. However, being an app note it of course remains on the surface of this complex topic.
The App note has a complementary workspace with all the different components that are used to discuss the issue. You can find this workspace on Github. If you want to understand the many patterns better then load this workspace in Bndtools and run the tests. (As a note, all components use service=… only to make them easier to test.)