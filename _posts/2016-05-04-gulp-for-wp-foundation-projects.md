---
layout:     post
title:      "Gulp.js for WP/Foundation projects"
date:       2016-05-04 21:30:00
author:     "Jayden"
header-img: "img/gulp-post-bg.jpg"
comments:   true
---

It wasn't until very recently that I stumbled across the wonder that is Gulp.js. For too long my development workflow consisted of roughly the following:

- write vanilla html & css
- alt-tab to a browser window rendering my project via the local filesystem (or python's SimpleHTTPServer if I ran into javascript issues)
- reload the page
- note the changes I needed to make
- alt-tab again
- make the changes
- repeat a million times until the project is complete
- upload via an FTP client
- Make changes and re-upload as necessary

Needless to say, this was not the best method of development. But as a self-taught developer in the early stages of my career, I really didn't know any better. Most of my clients never asked about my methods and really didn't care as long as the end product was pleasing to the eye. And while it may have been time consuming and monotonous, it didn't seem like a huge deal. I didn't realize that there was a better way. Besides, I was getting paid hourly, so why try to speed things up right?

(I kid.)

When I first encountered Gulp, it kind of blew my mind. It allowed me to combine many of the small tasks I had previously done by hand into a simple script and make them run automatically. All of a sudden I didn't need to reload the browser or upload files to a server manually, instead I could have Gulp take care of those things for me.

I've quickly fallen in love with the flexibility and ease of using Gulp to manage tasks in my workflow. Over the course of the past few Foundation projects I've done, I've developed a standard gulpfile that I use to take care of both local and remote development. It supports quite a few useful features namely:

- a feature packed dev server
- sass compilation (with sourcemaps and autoprefixer)
- ftp deployment

Best of all, all of these things happen on the fly, which saves a bucketload of time.

I've included the file below for you to check out and maybe use in your own projects. Feel free to modify it and add things to your heart's content! If there's anything you think I should add, or you you have any questions/comments/criticisms, I would welcome your input in the comments. Check out the further reading section if you want to learn more about integrating Gulp.js into your workflow.

<script src="https://gist.github.com/jaydenwindle/71659e28d40cc8a56ce343b21eca5715.js"></script>

<a href="https://gist.githubusercontent.com/jaydenwindle/71659e28d40cc8a56ce343b21eca5715/raw/d390ed6af6ab377739a451b49ab6171b14e62422/gulpfile.js" download="gulpfile.js">Download file</a>

### Further Reading
[Intro to Gulp.js](http://www.sitepoint.com/introduction-gulp-js/) - Sitepoint  
[Automate Your Tasks Easily with Gulp.js](https://scotch.io/tutorials/automate-your-tasks-easily-with-gulp-js) - Scotch  
[Gulp vs Grunt. Why one? Why the Other?](https://medium.com/@preslavrachev/gulp-vs-grunt-why-one-why-the-other-f5d3b398edc4#.75ascaegk) - Preslav Rachev via Medium
