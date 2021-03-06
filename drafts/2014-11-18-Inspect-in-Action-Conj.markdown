---
layout: post
title: "Inspect in Action; Conj"
date: 2014-11-14 17:30
comments: true
categories: 
---
Last week I published my first Clojure library, **[inspect](https://github.com/matthiasn/inspect)**. I started using it over the last couple of days and I share my experience with you today. Also, I will give a brief outlook over my next couple of weeks, which includes me attending the Conj and also me giving a talk at Clojure Exchange in London in December.

<!-- more -->

So I have started using **[inspect](https://github.com/matthiasn/inspect)** in my **[BirdWatch](https://github.com/matthiasn/BirdWatch)** application. Check the footnotes if you wonder what this BirdWatch application is.

--
in footnotes?
Last year in March, I had applied for a job as a software engineer working in Scala, and it bothered me that I had no projects to show. I wanted something realtime-ish so I started looking for streaming data sources and quickly found the Twitter Streaming API. Initially, that project was only meant for that one job interview, but it has soon developed a life of its own. In a way, it feels like adopting a stray dog, in a good way. I never meant to keep it, but its cute and fun. So I just kept working on it to learn about different approaches. The initial one was written in Scala and Play Framework on the server side, with the client using KnockoutJS. An AngularJS version followed, that one was decribed here. After some brief experimentation with ScalaJS, I rewrote the client using ReactJS and plain JavaScript. Then, for a brief moment, I tried writing a ClojureScript client, while still keeping the Scala backend. Now, finally, I rewrote the entire system in Clojure and ClojureScript and I like this one the most. 
--





At **[Clojure eXchange](https://skillsmatter.com/conferences/1956-clojure-exchange-2014)**, I will have a talk about this application and about my **["Building a System in Clojure"](http://matthiasnehlsen.com/blog/2014/09/24/Building-Systems-in-Clojure-1/)** series that I started about this application here on this blog. I am looking forward to that opportunity a lot. There is also still a lot of work to do. My recent detour into writing the inspect library was well worth it, but at the same time that kept me from developing BirdWatch further. But I feel like the benefit of having inspect will outweigh the extra work rather sooner than later.






With all this work coming up, there is probably not going to be an article next week, I shall put all my energy into bringing BirdWatch to where I want it to be for the presentation in London. 



Once **[Clojure eXchange](https://skillsmatter.com/conferences/1956-clojure-exchange-2014)** is over, I will need a couple of days off and finish a couple of other projects. Then from January on, I will be available for new projects. So if you plan on building some kind of real-time(ish) application and need help with that, you should come talk to me at the conj or in London. Or shoot me an email, the address is on my GitHub profile.

Okay, that's all for today. Have a great week,
Matthias
