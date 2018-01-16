---
title: My Skills
subtitle: Here are some things I can do.
icon: fa-graduation-cap
permalink: /skills
order: 2
---

### Front-end

* Jekyll Themes
  * Build a [new Jekyll theme](https://github.com/chrisbobbe/jekyll-theme-prologue) from a single-page web template written in HTML5, Sass, and JavaScript
  * Design an [intuitive, well-documented API](https://github.com/chrisbobbe/jekyll-theme-prologue/blob/master/README.md) for building a homepage with this theme
  * Favor universal access by changing banner image content from CSS `background-image` to `<img>` tags with alt text, scaled with `object-fit`
  * Make SEO easy by piping users' config variables to meta tags with Liquid templating
  * Extend the web template to multiple pages to meet Jekyll users' blogging needs
* React
  * [Migrate](https://github.com/chrisbobbe/react-auth-sandbox) a single-page app's client-side routing from React Router 3 to 4
  * Follow best practices in React with views in a component hierarchy where [data flows down](https://reactjs.org/docs/thin king-in-react.html)
  * Take full advantage of React before carefully adding Redux
* WordPress
  * Deploy WordPress manually to Heroku and connect it to an Amazon RDS instance running MySQL [^2]
  * Configure SSL between the database and Heroku with keys and passwords stored in Heroku Config Variables
  * [Deploy WordPress](http://www.mild-mandarin.com/) using a hosting provider such as GreenGeeks

### Full Stack

* Java
  * Implement the Model-View-Controller pattern in a full-stack web app [^1]
  * Design an Entity Relationship Diagram (ERD) to describe database structure
  * Use a DAO interface to send prepared statements to a PostgreSQL database
* Google, Udacity
  * Win a [scholarship](https://www.udacity.com/grow-with-google) (Jan. to March 2018) to learn full stack mobile-first development techniques and patterns (such as offline-first for slow connections)

### Other

* I make myself more productive with code
  * I use the Gmail API to [keep my mail neat](https://gist.github.com/chrisbobbe/072add64f2254c7a22b21b77eceb874c)
  * I made a [custom TypeScript app in IFTTT](https://gist.github.com/chrisbobbe/4d2f79af65efdfa31e49bf00f983c779) connects my Fitbit with the productivity tracker Beeminder to make sure I sleep enough
* A full 12-week batch at the [Recurse Center](https://www.recurse.com/) in New York, writing code for projects full-time
  * I grew by immersion in conversations far above my level
  * I learned to [ask good questions and push myself](https://www.recurse.com/manual)
  * I spent lots of time learning JavaScript properly (ES5 and ES6)
  * I pair programmed on a [Fortune's Algorithm (Voronoi diagram) implementation in C++](https://github.com/mtn/voronoi) for three weeks
  * Studied machine learning theory
* Well-rounded formal education:
  * [B.A., English, Haverford College](https://www.haverford.edu/english)
  * [High School Diploma, North Carolina School of Science and Mathematics](https://www.ncssm.edu/)

--------

[^1]: Thanks to Revature and their [PubHub project](https://app.revature.com/projects), which taught me a lot about Java and industry best practices.
[^2]: I actually moved this project because Heroku's file system [resets](https://devcenter.heroku.com/articles/dynos#ephemeral-filesystem) every day, so it wasn't great for WordPress where the smallest change in themes or plugins means writing to a file on the app server. The project is now hosted [here](http://www.mild-mandarin.com/) by GreenGeeks.
