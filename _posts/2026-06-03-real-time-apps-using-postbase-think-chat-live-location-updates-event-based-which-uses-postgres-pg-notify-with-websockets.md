---
layout: post
comments: true
title: Real-Time Apps using Postbase (think Chat, Live Location Updates, Event Based) which uses Postgres pg_notify with WebSockets
---

*by a human - no AI was used*

[View Post](https://umrashrf.github.io/real-time-apps-using-postbase-think-chat-live-location-updates-event-based-which-uses-postgres-pg-notify-with-websockets/)

I just integrated live location updates in a two-sided marketplace app using Postbase and it's so satisfying to watch the location updates just go through from one user to another in real-time! Knowing so many different parts are working all together behind the scenes to make that happen.

That is, Postgres < pg_notify < Web Sockets < Express.js/Node.js < Postbase < Nginx.

Not to mention the Database Migrations using node-pg-migrate, the serializing and deserializing of JavaScript to SQL using Postbase integrating Web Sockets with them and making them run over HTTP using Nginx rewrites! And to put it in a user interface using React/Preact app.

Before Postbase, I was using Firebase which is a great product by Google but it is vendor locked. With the invention of Postbase, I am using it for all my open source and commercial projects and it feels really good to own your infrastructure and data. Postbase is also open source! So anyone can grab the copy and run their own infra on it.

**Know what is Postbase? Find the link and post in the comments below. The right link will get a like and wrong link will get crickets.**
