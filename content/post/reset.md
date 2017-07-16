+++
title = "Reset"
tags = ["hugo" , "caddy" , "GCP" ]
draft = false
date = 2017-07-15T19:10:40-05:00
author = "TCB"
+++
Well, well, well, this has been far too long in the making. That's the
problem when you work a lot. Things slip, things slide, things that need
to get done take precedence over things that still ought to get done. 

Over the years I have hosted a few sites for 'friends and family' type
people. Often do-gooder organizations that didn't have a lot of
resources or personal friend who didn't want the hassle of maintaing a
site. This led to various forms of static, dynamic, blogged and
non-blogged sites under more than one roof. The thought process of doing
something on one when the others were in some less than ideal state just
got tiresome. 

The solution, for me at least, was moving things to one place with
similar tech. All of those sites are now hosted on a Google Cloud
Compute instance. They all are served by Caddy. And they are all built
with Hugo. They all run cron jobs and clone git repos and use rsync and
all of that too. For my less technical users, as long as they can edit a
markdown file and use the Github web site, they should be pretty close
to self-serve. 

This was all driven by the idea that for them (and maybe more for me) we
need to concentrate on content. There are some things I really don't
like about Hugo, but its greatest strength, in my opinion, is that
content is about as distinct from site building and tech as possible. My
hope was to get to where I could just write when it's time to write. And
so could everyone else. At this point, between Caddy and Hugo we should
be spitting out roaring fast, HTTP2 static sites with much more time
spent on writing. 
