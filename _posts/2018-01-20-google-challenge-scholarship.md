---
layout: post
title: Google Challenge Scholarship
subtitle: And Some ES5 Nostalgia
author: Chris
---
I thought of starting with "Welcome to my first blog post!" because that's how I started the last three times, with some variation. I've decided enough with the ceremony, I should just dive in. But do consider yourself welcome to my humble blog.

I've zoomed through the Grow with Google Challenge Scholarship on Udacity, probably faster than I should have. We're allowed three months, and I finished in less than a week since I have so much time on my hands. Still, if I hope to be selected for the next step, the [Mobile Web Specialist scholarship](https://www.udacity.com/course/mobile-web-specialist-nanodegree--nd024), I need to stay active on the forums and help other people out. This will be a good way for me to review the material, so it sounds like a plan.

I learned how to make an app offline-first using service workers. This helps mobile users a lot because some content will load (maybe old content, but still) in low or no connection areas. No more "lie-fi"!

The rest of the course was about all the new features in ES6. I've been a fan for as long as I've worked with JavaScript, since I started after ES6 was released. Strangely, I got a bit frustrated with the new object method definition shorthand. The old way:

```
myObj = {
  name: "foo",
  hairColor: "brown",
  someMethod: function() {
    // method code here;
  }
}
```

can now be written like this:

```
myObj = {
  name: "foo",
  hairColor: "brown",
  someMethod() {
    // method code here;
  }
}
```

I see that it's shorter, which might make it better, and I've [read](https://ariya.io/2013/03/es6-and-method-definitions) that it brings method definitions more in line with how `get() { ... }` and `set() { ... }` are defined in ES5, which are both fair points. But I'm used to reading JavaScript objects as key-value pairs, and part of me misses the colon. What's more, given the new kind of [`this`-scoping](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch2.md#lexical-this) we see in arrow functions (also ES6), I have some trouble processing a strange third thing that uses neither the `function` keyword nor the arrow `=>`. Even now, I'm not sure I can say confidently how `this` would work inside a method defined the new way. I'm sure I will one day.
