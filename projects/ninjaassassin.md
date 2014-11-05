---
layout: page
title: "Ninja Assassin"
description: "Project page for Ninja Assassin"
tags: [projects]
---
{% include JB/setup %}

Ninja Assassin is a ninja "roguelike" game developed for Cal Poly Pomona's 18th Annual IT Competition.

For Cal Poly Pomona's 18th Annual IT Competition, my team of 3 members was given three weeks to build a game using only HTML5 and jQuery. The game was supposed to be able to function on all modern browsers, including mobile browsers. In addition to developing a game, we were also tasked in developing a website to host our game on. The website was supposed to include a user management system, allowing users to log onto the website and save their high scores in the game.

The game was implemented using HTML5 for the game graphics and Javascript with jQuery to handle the game logic. The jQuery TouchSwipe plugin was used to add mobile-friendly controls to our game. Our game communicated with our site's API through AJAX calls to save and retrieve high scores. 

Our website was implemented using Laravel PHP to manage the site's back-end as a Model View Controller. Laravel also provided a secure user authentication system with secure Bcrypt hashing for storing passwords. Additionally, we utilized a MySQL database for storing our user data. Our website and game was hosted on OpenShift, a cloud application platform. 


- <a href="https://github.com/jraguilo/ninjaassassin">View Game Code on GitHub</a>
- <a href="https://github.com/suupersal/ninjaassassin2">View Site Code on GitHub</a>
