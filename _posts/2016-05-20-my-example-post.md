---
title: A jekyll site using github pages (this site)
layout: post
time-to-implement: An evening
---
So this is my first blog and what better way to start it than explaining how i got this site going :) 

## Jekyll the static site generator ##
So [Jekyll](https://jekyllrb.com/) is this very cool tool that creates static pages using ruby. Think of it as a CMS without all of the pain (well okay there was a bit of pain, but not compared to a classic CMS). Obvioulsly its not as powerful as a fullblown CMS, but still really cool if you want to do simpler stuff.
It works by using template files to create actual static pages, a little bit like [Handlebars](http://handlebarsjs.com/). So input is a template files and posts written in a language called Markdown and out comes a generated static page. 

An example of a written post in markdown:
![drawing]({{ site.baseurl }}/img/jekyll-post.PNG)

An example of a post template:
![drawing]({{ site.baseurl }}/img/jekyll-post-template.PNG)

With the two above files this is the output:
![drawing]({{ site.baseurl }}/img/jekyll-output.PNG)

## Creating this blog ##

I found a template for Jekyll on [jekyllthemes.org](http://jekyllthemes.org/) that looked really nice. Cloned it, ran bundle install and hit so many error that i found another theme and another one, and then i found [Airspace](http://jekyllthemes.org/themes/airspace/). Pretty nice, but i just needed it as a base, so now everything is being rewritten. The styles, posts and layouts. 

## Deploying to Github ##

With my new blog based [Airspace](http://jekyllthemes.org/themes/airspace/) i took to Github. So Github has this really really cool and surprisingly easy way of getting your own page. Simply branch out from master into a branch called gh-pages. When you have pushed the jekyll site to github it automatically detects it is a Jekyll site and builds the _site which is a folder that contains the built site. Like a build folder with all your compiled css and uglified js. After some time you can go to https://your-github-username.github.io/repo-name/ and see your cool new blog!!11!!1!


Awesome!!11!!1