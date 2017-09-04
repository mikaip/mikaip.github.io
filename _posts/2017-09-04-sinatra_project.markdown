---
layout: post
title:  "Sinatra Project "
date:   2017-09-04 04:17:28 +0000
---


I've finally submitted my Sinatra project and it was somewhat more enjoyable to work on than the first CLI project. As usual I had a hard time coming up with an idea but finally decided on a very simple one - essentially it is a student login app for students to register or edit their courses and books (reading materials?). This is actually relevant to me currently because I'd like to create a (much more extensive) student/teacher/admin database and login system, with course management, grades, etc., for a reading and writing program that I am involved in. Although this was much simpler, I thought of it as a stepping stone to the app that I will hopefully work on in the future.

A user(student) can sign up or log in, and can add a new course. Users can only edit or delete a course that belongs to them. For each course they create, they can start adding books which they can edit if they had created that book.

Some of the most difficult parts for me were implementing things like authentication, validations, and error messages. After looking at the provided example apps for assistance, I was able to use new helper methods like redirect_if_not_logged_in, which I had not known about before (or I just couldn't recall learning about it). Another example is validating through params which I was not as familiar with. The idea of error messages was another that I was a bit confused on so after googling around, I saw that I can insert something into the layout.erb to show the error message, such as when the user needs to be logged in. I also saw that there is a flash gem which I wanted to use, but unfortunately I could not get it to work... anyway I was able to get the error message to work and learned several new things. These concepts are still quite confusing for me. Setting up all the routes and redirects in the controllers were tedious at first but I began to feel more confident the more I repeated them, so it was very helpful.

Another difficulty I had was with the associations, especially for Book and Course. A User has many Courses; a Course has many Books. The association between User and Course was relatively fine but I wanted to add a third model in Book, and I started to sort of regret adding this since the requirement was only up to courses/:id and I thought I ws messing up the whole app. But it was a challenge that was good for me to learn. I hope I did everything correctly, but I think I gained a more solid understanding by writing the validations and associations for this. Overall, I had fun working on this app and being able to see each mistake and each change by running shotgun, and I ended feeling more confident than on my previous project.
