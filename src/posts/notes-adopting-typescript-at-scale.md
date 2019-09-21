---
layout: layouts/post.njk
title: 'JS Conf: Adopting Typescript at Scale'
date: 2019-08-08T20:21:04.318Z
tags:
  - notes
---
Brie Bunge takes us through Airbnb's approach to adopting Typescript. This is worth a watch to get a grasp of the process even if you're not using Typescript.  

Checkout the video here: https://youtu.be/P-J9Eg7hJwE

[![Adopting Typescript at Scale](https://img.youtube.com/vi/P-J9Eg7hJwE/0.jpg)](https://www.youtube.com/watch?v=P-J9Eg7hJwE "Adopting Typescript at Scale")

## Notes

* What doe scale mean in this context? Hundreds of developers at Airbnb now use Typescript as their primary language for front-end development.

* 2m lines of JavaScript needed converting, over 100 internal npm packages. 1300 engineers 200 of which work on the front-end.

* The idea was raised at the front-end working group meeting where they talk about new technologies, make and discuss proposals.

* These are deliberate decisions about what they commit to as a team.

* They used pilot teams first who were then sent a survey to see if they should keep using it.

* There are types maintained in a public package for packages which aren’t typed with Typescript. Sharing is caring.

* Codemods can help you do large refactors.

Impact of introducing Typescript:

* Fewer bugs - externally it had been reported to reduce number of bugs by 15%. After analysis of recent bugs Brie found that 38% of those bugs would have been preventable with Typescript.
* A better developer experience.
* End to end type safety as types can be used across front and back-end.

If you want to do something similar:

* Gather evidence and support
* Gradually introduce change
* Be inspired to make the change you are passionate about
