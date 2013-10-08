---
title: Week 3 Retrospective
date: 2013-10-04 15:09 UTC
tags:
---

####[SalesEngine](http://tutorials.jumpstartlab.com/projects/sales_engine.html)

This week, we created a data reporting tool, similar to [EventReporter](/2013/09/20/week-1-retrospective.html),  that was able to do the following:

* load CSVs
* Retrieve data by select criteria
* Retrieve and aggragate data from CSVs, filtered by select criteria
* Write business intellegence logic finding things such as:
  + Revenue by date
  + Best customer
  + Best day

####Work Patterns

This week, I was paired up with [Will Mitchell](wvm-gschool-blog.herokuapp.com) who is exceptionally talented. We worked well together due to our commitment to our workflow. We both we took turns at the keyboard switching during our 25 minute pomodoro sessions.As one person hacked away at the keyboard, the other would help work through the problem conceptionally, figuring what the best way was to go about the problem. It is similar to being on road trip where one person drives and the other person navigates. Both roles are important and allow each partner to add value during the session. Also, having a pair help relieved stress, knowing that if you get stuck on a problem, someone is there to help. In addition, being able to have two sets of eyes on a bug increased our chances of spotting the error, or having an Aha moment that saves the day.

The project itself was fun and frustrating at the same time. Will and I picked up early on that there was going to be alot duplication and patterns in the code base and thought it would interesting to to try some [metaprogramming](http://en.wikipedia.org/wiki/Metaprogramming) to avoid the repetitiveness. It was a great experience, thinking about how to mass produce code and how to execute that. However, it was a double edge sword; we quickly found out that it is harder to troubleshoot. When you write code that writes code, if something breaks, it breaks everywhere. At one point in time, we lost half of a day fixing a bug which affected half of our project.

Having a SQL background, my mind wanted to solve this project using my previous experience. There were feature requests I have done verbatim in SQL at my old [job](http://livingsocial.com), which is understandable given the origin of this [project](http://hungryacademy.com/). However, I was able to turn this into advantage, by leverage my understanding of database structures to help work through these features. I understand that this was one of points of this project teaching us how databases work by making us do it in a more manual fashion.

####Reflections

Having now been at gSchool for 4 weeks now, SalesEngine is something I did not think I was capable of doing at the start of the program. Yet, the instructors here have helped unlock my pontential. Going into this project I felt condfident about my abilities and what was asked of me was within my scope. Also this project made me appreciate my prior experiences. Knowing technologies such as SQL, allowed me automatically create schema of how the data  related to each other. It was an awesome feeling that something I randomly picked up a few years ago, turned out to valubale skill today.


####[SalesEngine Repo](https://github.com/wvmitchell/sales_engine/)
