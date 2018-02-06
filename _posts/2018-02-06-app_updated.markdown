---
layout: post
title:      "App updated"
date:       2018-02-06 18:35:28 +0000
permalink:  app_updated
---


My previous rails assessment was a simple gradebook-type app where students, teachers, and admin can see a catalog of courses, assignments, and grades. The goal of this project was to expand upon it with jquery and ajax. It was challenging, and I think that the way I had structured my rails project made it seem more complicated to me but i tried to keep it simple.

I basically centered the new features around the assignment model. For the requirement of using a form to create a resource via an AJAX POST request, I was initially unsure of how to go about it because my app doesn’t have features like adding comments or notes. So I thought about creating a new comments feature just for this requirement, but then I stuck to using a form to add a new assignment, which was already there, since that would be more applicable to the app. I changed it so that it would post with ajax and create a new js model object of an assignment where only admin can post. I think this was the hardest part for me because it would not read the json request. I added a "more" button feature (link) that shows more information about a course when clicked on, without refreshing. 

I did not use templates this time but I think I’ll need to get some practice using them so I will try implementing handlebars.  And I would REALLY like to make the app look more professional and this was something I had hoped to work on from the rails project too, but it was…not easy. I figured that I should complete the requirements first, again, which already took me much longer than I had planned. So I will hopefully get to it soon!
