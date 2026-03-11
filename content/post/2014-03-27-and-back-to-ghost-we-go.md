---
date: 2014-03-27
title: And Back to Ghost We Go
tags: ["blogging"]
---
There's two types of blog posts in this world:

  * posts about not posting;
  * and posts about changing a blog's backend.

Unfortunately this post isn't going to be any different since I'm going to talk about the slight change I've had to make to the backend of my blog. Don't worry though, it's not going to be overly long or technical!

A while back I posted about [how I was running on Octopress](/post/2014-03-06-moving-to-octopress/) and to be honest it was a wonderful system to work with. You could set up posts and preview how everything would look before deploying it to our hosting provider and it was pretty easy to customize while at the same time packing a lot of power into its code.

The problem arose when I tried to update it and ran into error messages by the dozen. Now in my defence I'm not excellent a code hacker of any sort and I'm also fairly new to Git and that's a combination that means using a hacker orientated system like Octopress is a recipe for disaster. I have been able to sort out most issues so far though using a lot of the community sites and also a bit of Google-fu.

Unfortunately when I tried to upgrade my Octopress instance I just ended up making it worse and worse with each terminal command I threw at it. Eventually I decided to throw in the towel and admit defeat.

So my next decision was how to resurrect my blog and what to use for its backend. I've been running Ghost for one of my other sites and while it's still not as stable in terms of the features it offers I thought that I may as well take the plunge and move everything over to it since I was originally planning to eventually transfer the site anyway.

Luckily the fact that both Octopress and Ghost stores all posts and pages in markdown makes it a breeze to swap content between the two. The hardest (or at least most tedious) part was ensuring that all the posts had the correct date for when they had been originally posted. Other than that I just needed to copy and paste each post and check that each post was assigned an appropriate tag before making them live on the site.

There were a few other tweaks I had to do such as adding in the code for Disqus comments and Piwik analytics but that was a simple matter of pasting the appropriate code snippet into a layout file and everything worked without a hitch. I think that's one of the best features of Ghost, it's extremely customizable and that's even before it has proper app support!

I was hoping to hold off on a full shift over to Ghost until it had more robust static page support and was a bit more mature but at least this early change means that I won't have to worry about transferring over a large number of posts if I'd waited until the end of the year for instance.

In the meantime if you stumble across any rough edges or bugs on any pages or posts please let me know.