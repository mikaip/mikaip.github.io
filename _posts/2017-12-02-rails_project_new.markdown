---
layout: post
title:      "Rails project new"
date:       2017-12-02 22:28:53 +0000
permalink:  rails_project_new
---

I decided to redo my project with a similar but slightly different idea and I think it is ready for review. It was easier and quicker setting up the basics this time around, but I still had some difficulties with the many associations and models. This time I used Devise Roles (activerecord enum?), recalling the lab that we had done, and it made some things much easier since I can access each role with simple automatic methods like “User.admin?” and more. Another huge difference was that I added additional layers of nested resources. Although I did not want to overcomplicate things and mess it up, I think I was able to get through it, for example: semester/1course/1/assignment/1. A lot of these steps were very repetitive, as Rails apps tend to be, but it was good practice!  I also gained more experience with Devise while  using a separate users controller with my own routes.

Some features I would like to add: adding another role with separate features (guardian/parent), confirmation before deleting certain things for admin, various options for grades, adding name attribute(!), better styling, and more simplified routes. 
