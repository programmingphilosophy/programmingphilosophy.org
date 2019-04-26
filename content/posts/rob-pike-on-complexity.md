---
title: "Rob Pike On Complexity"
author: "Jade Meskill"
date: 2015-03-22T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

The following is an excerpt from Notes on Programming in C by Rob Pike

**Complexity**

Most programs are too complicated - that is, more complex than they need to be to solve their problems efficiently. Why? Mostly it&#39;s because of bad design, but I will skip that issue here because it&#39;s a big one. But programs are often complicated at the microscopic level, and that is something I can address here.  

**Rule 1.** You can&#39;t tell where a program is going to spend its time. Bottlenecks occur in surprising places, so don&#39;t try to second guess and put in a speed hack until you&#39;ve proven that&#39;s where the bottleneck is.  

**Rule 2.** Measure. Don&#39;t tune for speed until you&#39;ve measured, and even then don&#39;t unless one part of the code overwhelms the rest.  

**Rule 3.** Fancy algorithms are slow when n is small, and n is usually small. Fancy algorithms have big constants. Until you know that n is frequently going to be big, don&#39;t get fancy. (Even if n does get big, use Rule 2 first.) For example, binary trees are always faster than splay trees for workaday problems.  

**Rule 4.** Fancy algorithms are buggier than simple ones, and they&#39;re much harder to implement. Use simple algorithms as well as simple data structures.  

The following data structures are a complete list for almost all practical programs:

array   

linked list   

hash table   

binary tree

Of course, you must also be prepared to collect these into compound data structures. For instance, a symbol table might be implemented as a hash table containing linked lists of arrays of characters.  

**Rule 5.** Data dominates. If you&#39;ve chosen the right data structures and organized things well, the algorithms will almost always be self­evident. Data structures, not algorithms, are central to programming. (See The Mythical Man-Month: Essays on Software Engineering by F. P. Brooks p. 102.)  

**Rule 6.** There is no Rule 6.
