---
title: "Refactoring, Rewriting, Rearchitecting. Oh My!"
author: "Jade Meskill"
date: 2015-03-09T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

I hear the term &#34;refactoring&#34; nearly every day. I usually want to shout in my best Inigo Montoya impression: &#34;You keep using that word. I do not think it means what you think it means.&#34;  

A brief history of refactoring:  

While the exact origins of &#34;refactoring&#34; as it applies to code is unknown, it obviously borrows from the idea of factoring in mathematics. Factoring is the process of reducing an object (number, polynomial, etc) into it&#39;s simplest parts. An example: x^2+3x-4 factors to (x+4)(x-1). The result of the factoring is made up of much simpler building blocks. However, the expression retains is original meaning.  

Refactoring your code follows a similar approach: reduce complexity of the code to simpler base parts, yet the behavior of the original code are not changed. In 1991 William Griswold published his Ph.D. dissertation titled &#34;[Program Restructuring as an Aid to Software Maintenance](http://cseweb.ucsd.edu/~wgg/Abstracts/gristhesis.pdf)&#34; , followed by William F. Opdyke in his &#34;[Refactoring Object-Oriented Frameworks](http://www.ai.univ-paris8.fr/~lysop/opdyke-thesis.pdf)&#34;, published in 1992. These papers make the case for automated refactoring tools and demonstrate a variety of basic (as well as advanced) refactorings. They both also establish the idea that the refactoring should be &#34;behavior preserving.&#34;


> 
> The focus of the thesis is on automating the refactorings in a way that preserves the behavior of a program. The refactorings are defined to be behavior preserving, provided that their preconditions are met. Most of the refactorings are simple to implement and it is almost trivial to show that they are behavior preserving
> 


  

So, keep in mind, a refactoring is intended to preserve the existing behavior of the code, whether through manual or an automated process.  

Anything beyond that is rewriting or rearchitecting. You can&#39;t always refactor your way out of a mess. Sometimes the system itself must be changed in order to break it down into simpler building blocks.  

To get a deeper look into refactoring, consult the comprehensive &#34;[Refactoring: Improving the Design of Existing Code](https://www.goodreads.com/book/show/44936.Refactoring?from_search=true)&#34; by Martin Fowler  

Grandpa, tell me a story &#39;bout the good days:  

At Integrum we had been cultivating a style of pair-programming that we lovingly referred to as Asshole Driven Development (or ADD). A simple explanation is: using ping-pong pairing and Test Driven Development, Person A writes the simplest possible test that could possibly fail. Person B then tries to find the simplest possible code that will make the test pass, including copying and pasting the test case as the result. Person B then writes the next simplest possible test that could fail, Person A implements. Rinse, repeat. It becomes a fun game to see how simple you can make the solution, keeping the pair programmers fully engaged.  

This is all well and good, however in 2010 Uncle Bob Martin published his [Transformation Priority Premise](http://blog.8thlight.com/uncle-bob/2013/05/27/TheTransformationPriorityPremise.html), suggesting that every Refactoring has a counterpart called a Transformation. mind = blown


> 
> As the tests get more specific, the code gets more generic.
> 


  

Without re-explaining the entire TPP, the core idea that code transforms from specific to generic is extremely powerful. It frees the mind from having to know the solution before engaging in TDD. This can be one of the biggest barriers to getting started. We are used to starting with an implementation in mind and fixing it, rather than starting with an narrow, specific outcome working towards a generic solution.  

TPP + ADD = AWESOME!  

Check out Uncle Bob&#39;s post on [The Transformation Priority Premise](http://blog.8thlight.com/uncle-bob/2013/05/27/TheTransformationPriorityPremise.html), or watch the [Clean Coders Episode 24](http://cleancoders.com/episode/clean-code-episode-24-p1/show)  

What techniques are you using to refactor your code?
