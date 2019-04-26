---
title: "A Critique of the Remote Procedure Call Paradigm"
author: "Jade Meskill"
date: 2015-08-09T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

I have long disliked RPC, especially since I built a very messy XML-RPC/PHP system many years ago. This paper would have helped me out immensely.




 




[A Critique of the Remote Procedure Call Paradigm](https://www.cs.vu.nl/~ast/publications/euteco-1988.pdf) by Andrew S. Tanenbaum and Robbert van Renesse




 


> 
> 
> We propose the following test for a general-purpose RPC system. Imagine that two programmers are working on a project. Programmer 1 is writing the main program. Programmer 2 is writing a collection of procedures to be called by the main program. The subject of RPC has never been mentioned and both programmers assume that all their code will be compiled and linked together into a single executable binary program and run on a free-standing computer, not connected to any networks.
> 
> 
> 
> 
>  
> 
> 
> 
> 
> At the very last minute, after all the code has been thoroughly tested, debugged, and documented and both programmers have quit their jobs and left the country, the project management is forced by unexpected, external circumstances to run the program on a distributed system. The main program must run on one computer, and each procedure must run on a different computer. We also assume that all the stub procedures are produced mechanically by a stub generating program.
> 
> 
> 
> 
>  
> 
> 
> 
> 
> It is our contention that a large number of things may now go wrong due to the fact that RPC tries to make remote procedure calls look exactly like local ones, but is unable to do it perfectly. Many of the problems can be solved by modifying the code is various ways, but then the transparency is lost. Once we admit that true transparency is impossible, and that programmers must know which calls are remote and which ones are local, we are faced with the question of whether a partially transparent mechanism is really better than one that was designed specifically for remote access and makes no attempt to make remote computations look local at all.
> 
> 


  

Join the conversation on Facebook in [Programming Philosophy](https://www.facebook.com/groups/programming.philosophy/permalink/984280358289017/)
