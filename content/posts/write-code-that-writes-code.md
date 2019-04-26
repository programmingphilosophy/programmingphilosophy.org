---
title: "Write Code That Writes Code"
author: "Jade Meskill"
date: 2015-02-22T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

In [The Pragmatic Programmer: From Journeyman to Master](https://www.goodreads.com/book/show/4099.The_Pragmatic_Programmer?ac=1) by Andy Hunt and David Thomas, they have a list of the tips and checklists that appear throughout the book. #29 is: Write Code That Writes Code.  

In their section covering Code Generators they describe two different types: Active and Passive.  

Passive code generators run one time, and produce a result. From that point forward, any customizations that are done are outside the code generator. They go on to list some examples of passive code generation:


*   Creating new source files
*   Performing one-off conversions
*   Producing lookup tables and other resources


Active code generators are used each time the results are required. The result can always be re-generated again by the code generator. An example used in the book is dealing with a schema that is used to structure the database tables as well as the underlying code structures.


> 
> While passive code generators are simply a convenience, their active cousins are a necessity if you want to follow the DRY principle. With an active code generator, you can take a single representation of some piece of knowledge and convert it into all the forms your application needs. This is not duplication, because the derived forms are disposable, and are generated as needed by the code generator (hence the word active).
> 
On the complexity of code generators:

> 
> All this talk of active this and passive that may leave you with the impression that code generators are complex beasts. They needn&#39;t be. Normally the most complex part is the parser, which analyzes the input file. Keep the input format simple, and the code generator becomes simple.&#34;
> 


  

A couple years ago Roy van de Water and I tried an experiment: For two weeks, only write code that writes code. The goal was simple – write as little code &#34;by hand&#34; as possible and instead generate it by building our own code generators. That way, when we were wrong about the design of the class we were building, or the approach of the application, we would simply tweak the generators and run them again.   

We tried to keep the process simple so as to not over-engineer or waste a bunch of time.  

(assuming an existing generator did not exist)


1.  Write the new class we needed using Test Driven Development
2.  Create templates from the tests and source files
3.  Re-generate the class we had just written and replace it, ensuring it still works and tests all pass


That&#39;s it!  

We had a lot of fun trying to stick to the original goal and by the end we had a number of great generators that saved us days, if not weeks, of work on the rest of that project and on numerous projects since then.  

Have you tried something similar?
