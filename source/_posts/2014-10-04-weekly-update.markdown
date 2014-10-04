---
layout: post
title: "Weekly Update: Staging server for this blog"
date: 2014-10-04 19:06
comments: true
categories: 
---
This weekly update is mostly about organizational issues around publishing articles and getting feedback for unfinished articles.

<!-- more -->

The other day, I published the unfinished second article in the **Writing a System in Clojure** series for getting some preliminary feedback, but without announcing the article just yet. What I did not think about though was RSS aggregators that notice and pick up new content nonetheless, so that was a little less than ideal on my part.

Ideally, I should have a different way of publishing unfinished stuff in order to get feedback and then only have finalized articles on this blog.

So I came up with something different: a **staging server**. Just like I would want a test environment when developing an application, I also want a test environment for new articles. So I've removed the unfinished article from master for now and put the unfinished article here:

**[http://staging.matthiasnehlsen.com/](http://staging.matthiasnehlsen.com/)**

The implementation of this staging server took like 5 minutes. All I had to do was clone the directory on the server, check out a different branch in the cloned directory, create a new DNS entry for **staging.matthiasnehlsen.com**, and modify the **nginx** configuration so that the staging URL point to that new directory.

I got very helpful feedback so far, so at least publishing the unfinished article was still worth it. Right now I am working on illustrating the new article with some animations. I expect to be done with everything on Monday. I will also probably split the article in two as the current article is a little too long for my taste.

## Conclusion
While this little modification is probably not terribly useful for you, I feel like it will be much more convenient for my workflow. You can also check out the staging server to see new articles in the works. Just note that sharing links may or may not lead to **404's** later on as there is no guarantee whatsoever that those links will last. If they end up in master, they should, but the may well not.

Thats all for now. Have a great week,
Matthias