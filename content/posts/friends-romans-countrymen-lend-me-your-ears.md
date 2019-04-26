---
title: "Friends, Romans, countrymen, lend me your ears"
author: "Jade Meskill"
date: 2015-02-02T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

Discussion at: [https://www.facebook.com/groups/programming.philosophy/permalink/879945482055839/](https://www.facebook.com/groups/programming.philosophy/permalink/879945482055839/)  

   

I&#39;ve been dealing with the consequences of defects this week. Frustrated, I went back to the Holy Bible (aka [Extreme Programming Explained](https://www.goodreads.com/book/show/23827335-extreme-programming-explained)) for some guidance. I rediscovered this section in the Corollary Practices:  

   

**Root-Cause Analysis**  

   

Every time a defect is found after development, eliminate the defect and its cause. The goal is not just that this one defect won&#39;t ever recur, but that the team will never make the same kind of mistake again.  

   

In XP, this is the process for responding to a defect:


1.  Write an automated system-level test that demonstrates the defect, including the desired behavior. This can be done by the customer, by customer support, or by developers.
2.  Write a unit test with the smallest possible scope that also reproduces the defect.
3.  Fix the system so the unit test works. This should cause the system test to pass also. If not, return to 2.
4.  Once the defect is resolved, figure out why the defect was created and wasn&#39;t caught. Initiate the necessary changes to prevent this kind of defect in the future.


   

Taiichi Ohno has a simple exercise for this last step, the Five Whys. Ask five times why a problem occurred. So, for example,


1.  Why did we miss this defect? Because we didn&#39;t know the balance could be negative overnight.
2.  Why didn&#39;t we know? Because only Mrs. Crosby knows and she isn&#39;t part of the team.
3.  Why isn&#39;t she part of the team? Because she is still supporting the old system and no one else knows how.
4.  Why doesn&#39;t anyone else know how? Because it isn&#39;t a management priority to teach anyone.
5.  Why isn&#39;t it a management priority? Because they didn&#39;t know that a $20,000 investment could have saved us $500,000. 


After Five Whys, you find the people problem lying at the heart of the defect (and it&#39;s almost always a people problem). Addressing that problem and the other problems encountered along the way will give you some reassurance that you won&#39;t ever have to deal with this particular mistake again.  

   

I&#39;ve put formal regression testing, as opposed to just writing another test, in the corollary practices because most teams have too many defects to be able to invest heavily in resolving each of them. Once the defect rate is down to one a week or one a month, though, the investment is proportional and the team has practice improving in other ways. It is ready for a deeper look at its own weaknesses.
