---
layout: post
title: pre-compiling CSS
type: article
permalink: /blog/
---

1- What do you think of pre-compiling your CSS?

- CSS preprocessors takes the written code sass and converts it to CSS.

- I think that the pre-compiling process spares a lot of repeated code-writing which is pretty good.

2- Compare to regular CSS:

- A difference between pre-compiled CSS and CSS is that the pre-one makes the developer aware of typos and missing components within the code. for example by applying a color to an element without having the variable declared, that will be directly pointed out.

- One more difference is that Pre-compiled CSS offers the developer extended techniques compared to normal CSS.
It reduces both time and effort when applying and maintaining the CSS.

3- Which techniques have you used?

I’ve tried to use variables for my colors and font-styles.

4- Pros and cons?

Maybe It is efficient, time-sparing and best of all - it allows you to reuse code and maintain the DRY principle. But difficult to use for beginners like me. I do need special tools to compile the code. Debugging the code may also offer some problem since generated code line-numbers are not the same as within the source code.

5- What do you think of static site generators?
its too complicated thought jekyll includes alot of files which has confused me alot.

6-What is robots.txt and how have you configure it for your site?
It is a file that contains the areas of a website that search engine robots are forbidden from crawling.

7-What is humans.txt and how have you configure it for your site?
It is a simple text file that we put on the root of the site to show information about the people behind the site's production and maintenance.

8-How did you implements comments to blog posts?
I have created a new html file under includes-folder with the disqus-code which i have copied from my page there in disqus-website.
after that i have edit the configuration in the _config-yml and added :
disqus:
  shortname: mariakholi
