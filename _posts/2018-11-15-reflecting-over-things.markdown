---
layout: post
title: "Reflecting over things"
date:   2018-11-17 10:08:34 +0100
categories: tech reflections
---

# Reflections

#### What do you think of pre-compiling your CSS?
- Compare to regular CSS
- Which techniques did you use?
- Pros and cons?

##### Answer:
I find the process of working with SASS quite handy. Importing the partials, adding variables and working that way seems to be a more refined way than the old CSS "rotation". The Pros with doing this, apart from what is already written, would be it's way of structure. It feels to a step above the normal CSS code, even though CSS is coming closer and closer to functioning well without the use of pre-processors. If I am to mention a Con, I would say that there's more files and structuring to keep an eye on, however how the example of Minima SASS is setup, it feels very close to the way I worked with CSS before (in its structuring). 

------------------

#### What do you think of static site generators and what type of projects are they suitable for?

##### Answer: 
I haven't really worked with them before, I've always done my pages with pure code (html + css). Hence, the wonders of seeing it now. I really enjoy it (after the initial setup went through). It seems to be mainly suited for blogs, technical pages but really anything using a lot of static elements, with a desire to be run quickly and smoothly. I like it. 

------------------

#### What is robots.txt and how have you configure it for your site?

##### Answer:
robots.txt is, in short, used by "spiders" (example: search engines). It can set it to either allow or disallow all or certain spiders to get information from the webpage. Good to note is that it doesn't stop indexing, as its a different process.  I currently have it configured to allow all "crawling" (the name of the process that the spiders performs.)

------------------

#### What is humans.txt and how have you configure it for your site?
humans.txt is used to "describe" the person/people behind the webpage. It can contain information about names, email, contact info, software and components used, last update etc. Me, I used it as per the standard: Title (my name), site, twitter, location, last update etc. 

#### How did you implements comments to blog posts?
I used Disqus. I had a disqus user since before that I tied to a page called "shawspage" (through the Disqus homepage) with I referred back to this website by code. I might need to check when I put it on github pages so its pointing correctly. By adding code to the post.html under _layouts, it enabled the "Comment" function for my blogposts (as described earlier). 

#### What is Open Graph and how do you make use of it?
Open Graph Protocol is used to show a "preview" of the link and/or website you are posting, for instance on facebook or slack. As a standard, it should always contain a title, a type (for instance a video.movie), an image and a url, which is the cononical URL of the object to use as a permanent ID. This will also be looked at after I publish the site, might need to be changed. What I did, is that I added the four required "values", for instance I added a picture of a screen with code. 