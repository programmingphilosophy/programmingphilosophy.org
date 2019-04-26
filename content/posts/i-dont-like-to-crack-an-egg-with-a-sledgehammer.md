---
title: "I don't like to crack an egg with a sledgehammer"
author: "Jade Meskill"
date: 2015-02-02T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

From [A Discipline of Programming](https://www.goodreads.com/book/show/2276288.A_Discipline_of_Programming?ac=1) by Edsger W. Dijkstra:  

   

(Up to this very day there is among the more theoretically inclined computing scientists still a widespread feeling that recursive programs &#34;come more naturally&#34; than repetitive ones.)  

   

For the alternative way out, viz. providing the couple &#34;repetition&#34; and &#34;assignment to a variable&#34; with a sound and workable mathematical basis, we had to wait another ten years. The outcome, as is demonstrated in this monograph, has been that the semantics of a repetitive construct can be defined in terms of a recurrence relation between predicates, whereas the semantic definition of general recursion requires a recurrence relation between predicate transformers. This shows quite clearly why I regard general recursion as an order of magnitude more complicated than just repetition, and it therefore hurts me to see the semantics of the repetitive construct:  

 



while B do S



   

defined as that of the call:  

 



whiledo(B, S)



   

of the recursive procedure (described in ALGOL 60 syntax):  

 



procedure whiledo (condition, statement);  

begin if condition then begin statement;  

    whiledo (condition, statement) end  

end



   

Although correct, it hurts me, for I don&#39;t like to crack an egg with a sledgehammer, no matter how effective the sledgehammer is for doing so. For the generation of theoretical computing scientists that became involved in the subject during the sixties, the above recursive definition is often not only &#34;the natural one&#34;, but even &#34;the true one&#34;. In view of the fact that we cannot even define what a Turing machine is supposed to do without appealing to the notion of repetition, some redressing of the balance seemed indicated.
