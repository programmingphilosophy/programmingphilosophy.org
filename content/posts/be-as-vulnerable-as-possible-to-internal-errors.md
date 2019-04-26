---
title: "Be as Vulnerable as Possible to Internal Errors"
author: "Jade Meskill"
date: 2015-08-23T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

I&#39;ve been reading [ZeroMQ: Messaging For Many Applications](https://www.goodreads.com/book/show/15812621-zeromq). Even if you don&#39;t care about ZeroMQ itself, you should read this book. It has some of the most personality that I&#39;ve ever seen in a technical book, filled with challenging ideas presented in a humorous way.  

I ran across a great quote regarding error handling.


> 
> ØMQ’s error handling philosophy is a mix of fail fast and resilience. Processes, we believe, should be as vulnerable as possible to internal errors, and as robust as possible against external attacks and errors. To give an analogy, a living cell will self-destruct if it detects a single internal error, yet it will resist attack from the outside by all means possible.
> 


  

&#34;Processes ... should be as vulnerable as possible to internal errors.&#34;  

This is an easy trap to fall into. Trying to make code safe from itself usually leads to a debugging nightmare, and often times fails in new and spectacular ways. It seems counter-intuitive to be as &#34;vulnerable as possible,&#34; but I&#39;ve been testing this out on some of my recent projects with much success. The silent failures, the mystery zombie states, have all but disappeared. Now when I make a mistake, my code dies a terrible death, but it is very obvious where the problem lies and easy to fix.  

Join the discussion on Facebook in [Programming Philosophy]()
