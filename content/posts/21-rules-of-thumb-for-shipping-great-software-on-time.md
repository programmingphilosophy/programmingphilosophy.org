---
title: "21 Rules of Thumb for Shipping Great Software on Time"
author: "Jade Meskill"
date: 2015-02-02T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

[Roy](https://github.com/royvandewater) reminded me of this great article this week. It&#39;s long, but has some great content. If you want to get the bonus 2 and 1/2 rules, you can [watch the video](https://www.youtube.com/playlist?list=PL9B1543FBFFB18EDD):   

21 Rules of Thumb for Shipping Great Software on Time  

   

Jim McCarthy, Microsoft Corporation  

   

   

Shipping great software on time is a difficult but not impossible task. Elements you think would count the most count for very little. Development methodology, process, technical prowess, excellence of tools and depth of project management skills all influence the outcome of a software development project; but nothing indicates success as much as the manager’s ability to focus on a few critical and conceptually simple things. These things can be expressed as rules of thumb.  

   

I enumerate twenty-one of these rules of thumb. Pick a handful (or so), apply them, and your project will be more likely to succeed. I lump them into three groups: &#34;Shipping,&#34; &#34;Great Software,&#34; &#34;On Time&#34;. Duh. I cover them in a different order, because the concepts build a bit.  

   

   


On Time
  

   

**1. Don’t know what you don’t know.**  

   

It is essential not to profess to know, or seem to know, or accept that someone else knows, that which is unknown. Almost without exception, the things that end up coming back to haunt you are things you pretended to understand but didn’t early on. At virtually every stage of even the most successful software projects, there are large numbers of very important things that are unknown. It is acceptable, even mandatory, to clearly articulate your ignorance, so that no one misunderstands the corporate state of unknowingness. If you do not disseminate this &#34;lucid ignorance,&#34; disaster will surely befall you.  

   

Human nature is such that we dislike not knowing things that are important to our well being. Since there is so much we don’t know in a software project, the nearly universal tendency among developers and their managers is to gloss over or even deny altogether the extent of their ignorance. You should reward and treasure those who consistently make themselves aware of the list of relevant things that are currently unknown. It requires mental and psychological strength to resist the normal human cravings for certainty and order. It especially difficult to believe in uncertainty when things have a veneer of orderliness, which is often the case. Pseudo-order is a maladapted defense against uncertainty.  

   

The organization surrounding you will undoubtedly abhor uncertainty, would infinitely prefer pseudo-order and will make countless attempts to magically convert your ignorance to knowledge. Your job is to make uncertainty an unshakable fact, and to coerce the reshaping of the surrounding organization to cope with the uncertain situation. The organization must learn to thrive in an uncertain environment for its own well being.  

   

You should expend a great deal of effort making sure that all the people on the project are aware of their ignorance rather than naively converting it to falsehoods. Bear down on them until they realize they haven’t comprehensively assessed the unknowns. In the successful project, this is much easier in the early stages, or during times of change. This is no time for niceties. People ultimately prefer success even if disillusionment is a prerequisite.  

   

   

**2. Get to a known state and stay there.**  

   

The function of QA is to know (and articulate) the quality of the product at all times in the development cycle. This should be achieved by abbreviated, repeatable tests conducted daily, and full product sweeps conducted weekly or biweekly.  

   

It is not properly the job of QA to determine when a product is ready to ship; rather, the moment of shipworthiness in a product development cycle is evident to everyone involved, and is non controversial. This is because shipping has been the goal of the entire effort. Crossing the finish line, while it has intangible emotional and definite financial rewards, is no surprise when you’ve observed every single painful step toward it.  

   

The only reason you’ve been able to make these micro-observations is because you got to a known state and stayed there, and your QA is how you did it.  

   

Achieving a relatively accurate view into product status is a very challenging goal, requiring a highly motivated and competent QA team. It is also a pre-requisite for success. Many software development organizations have rudimentary or no real QA assets, and there is little that can be done for them until they make the appropriate investments in creating a modern development organization.  

   

A known state consists of all components having accurate status information at a given point in time. You know that it’s accurate because the status has been tested by QA.  

   

A developer articulating the status of his/her component is an exercise that does produce information, but if it happens to communicate the component’s status, it is only coincidental. This is someone else’s job.  

   

Status should consist of a comprehensive listing of tested and missing functionality, bug count sorted by severity, bug arrival rate, bug fix rate, projected total bug count, and other vital metrics.  

   

**3. Remember the triangle.**  

   

There are only three things that you are working with as a development manager: resources (people and money), features and the schedule. Changing one has an impact on at least one other axis, usually two. It is a simple enough matter to mentally run through the sides of the triangle, or force others to do so, when discussing any part of it. Since the people, the product or the schedule is almost always what you’re discussing, this means that you must constantly envision the triangle. This leads to the most fruitful line of thought.  

   

   

   

**4. Don’t go dark.**  

   

Some features have long development lead times, months or even years. Yet slips usually happen a little bit every day, and must be compensated for a little every day. This means that the granularity of development tasks must be such that deliverables are achieved at intervals sufficiently small that slips can be compensated for. A week is a long time to go without knowing what is happening. While micromanaging is always a danger, and will certainly be an accusation leveled against you from time to time, if the goal of the project is to ship great software on time, and if everybody accepts that goal as uppermost, they generally enjoy the chase. Team interdependency is also a powerful motivational force.  

   

   

**5. Use zero defect (ZD) milestones.**  

   

Organize the project around the concept a reaching milestones with zero defects. Zero defects does not mean that the product does not have bugs, or missing functionality; it means that the product achieves the quality level that had been set for that milestone. The product is tested to that effect. The essential point of ZD milestones is that nobody makes the milestone until everybody does, and nobody leaves it until everybody does. This enables the team to discover what aspects of the project are in trouble. Load balancing can occur. Awareness of unknowns rises.  

   

At a milestone, the team and its leadership also have the opportunity to perceive the whole project status simultaneously, to draw conclusions about erroneous practices, to remedy bad design decisions and to reorganize for peak performance. Shipping is just the final milestone. Though the external organization cares most about shipping, which adds special pressure to that milestone, the team develops extraordinary focus and introspection about each and every milestone.  

   

**6. Beware of a guy in a room.**  

   

This is really just a special case of &#34;Don’t go dark.&#34; Specialist developers who lock themselves away in a room, going dark for long stretches, are anathema to shipping great software on time. Without regard to their individual brilliance, before investing a developer with a significant assignment, it is essential that they understand and agree with the type of development program you intend to run. They must be capable of performing on a team, making their work visible in modest increments and subjecting it to scrutiny as it matures. Some people find this intolerable, and though there is a role for people of this disposition in the software world, it is not as part of a team devoted to shipping great software on time.  

   

There are many pathologies at play here as well as certain healthy patterns of creative behavior. One pathology is a type of savior complex that cannot be satisfied without blowing every single deadline but the last, and then emerging victoriously with a brilliant piece of work five minutes late. A more healthy pattern is that of the true innovator who is truly designing something great, but who has no personal resources left over for anything but the work at hand. Every ounce of psychological, emotional and intellectual energy is being consumed in the work itself. Teamwork, in this case, is an insignificant factor to a person immersed in this sort of creative experience.  

   

   

   

But whether or not the cause is healthy or bogus, the results are uniformly fatal to the professional development organization. Beware. Extricating yourself from this trap is nearly impossible.  

   

**7. Never trade a bad date for an equally bad date**  

   

Generally, you know you’re going to be late before you know when you’re going to be done. Further, everybody on the team and everybody they come in contact with knows you’re not going to hit the schedule. The pressure to reset the end-date (or the milestone date) is enormous. Even though your information is obviously better now than when you originally set your goal, it is probably insufficient to make a new schedule. This is because with each slip, you and your team are spending your credibility. It is essential that after a slip, the next milestone be hit. This is so the team believes in their ability to manage the project, and so that the reserves of credibility are rebuilt for later consumption.  

   

It is difficult to say precisely and in all cases when you should &#34;officially&#34; slip. A good general rule is that the schedule should be reset when the total extent of the slip is known for each component, the causes of the slip are understood, and remedies are in place. Usually, this takes the effort of the entire team and its leadership, and must be an explicit, focused activity. After this level of work is achieved, create a new, closer and more conservative milestone which the team is very likely to hit, and promulgate that. Avoid just sliding the schedule out. Your near-in milestone should be extremely realistic, and uncertainties about later milestones will remain and should be highlighted.  

   

**8. When slipping, don&#39;t fall.**  

   

Slipping is what happens when information that was unknown becomes less unknown. Though slipping is widely perceived to be a &#34;bad&#34; thing, it is the symptom of a good thing, as a fever is the sign of the body’s immune system at work. Although it is undesirable to have so many unknowns that slippage occurs, it is not an unusual situation, and may even be the norm. This is because much of contemporary software development is essentially experimental, i.e., new platforms, new operating systems, new programming technologies often coalesce on new programming projects to create a high degree of uncertainty.  

   

In order to avoid calamity, certain measures should be undertaken in connection with a slip. Ideally, one or more of the pre-identified unknowns caused the slip. It is important that everybody involved understand that the risk to the schedule had been known previously. Alternatively, it is essential to understand how the unknown/s had come to be overlooked. How this gap occurred should become part of the group knowledge for future success. Also, determine whether or not people are working on the correct things. Often, slips occur because members of the team become occupied with features of marginal consequence, or features that are not part of the core product message.  

   

If the slip was a surprise, your communications system is broken, and dramatic communications efforts are required. Large amounts of detail must be brought to the surface for everybody on the team to see. Assess the reality of all current near-term estimates. Expose denial. Team defensiveness will have to be pushed back for the purposes of group learning. Slips reveal your team’s weaknesses, presenting a good opportunity for insightful management and mentoring. Make sure that each individual who has a role in the slip receives the needed guidance and support.  

   

Slips are also an opportunity to re-evaluate the feature content and resource loads, generally with an eye toward decreasing the features and shoring up weaker areas on the team.  

   

A good slip should be a net positive.  

   

**9. Low tech is good.**  

   

A smaller effort is almost always more desirable than a larger one. Shipping great software on time requires that we value an understood solution much higher than one fraught with unknowns. Keep in mind that customers would almost always rather see progress than promises.  

   

**10. Design time at design time.**  

   

The product will ship when the design can be shown to be implemented. Developers and their managers often ignore the exigencies of time when creating a design. Instead, they should consider the implementation time as a critical design element. When evaluating alternative design decisions, the one that takes longer to implement is consuming more time and should therefore be disadvantaged in comparison to the alternative. This must always be weighed. Often, when appropriate design value is awarded to timeliness, implementation time can be substantially compressed.  

   

**11. If you build it, it will ship.**  

   

Conversely, if you don&#39;t, it won&#39;t. The product should be built every day, along with all setup scripts and on-line help, in a public place, where QA can conduct appropriate assessment of daily status, and the entire team can observe progress or its lack. This is the single biggest indicator that a team is functional and a product being developed.  

   

   

**12. Portability is for canoes.**  

   

And system software. Even discounting the added development burden, with the addition of each additional platform the job of QA increases substantially. While clever QA management can minimize the burden somewhat, the complexity of multi-platform support is beyond the reach of most development organizations. Place your bets. Demand multi-platform support from your system software vendor, then build your product on the absolute fewest number of platforms possible.  

   

   


Great Software
  

   

**13. Enrapture the customers.**  

   

Most software is a renewal business. Customers buy multiple releases over a relatively long period of time. As a consequence, the market has a deep understanding of your software and its flaws, and your organization and its flaws. Often, the market has grown uncomfortably dependent on software that doesn&#39;t meet its needs. In many software situations, customers spend hours per/day uncomfortably shoe-horning their lives into your product. As a consequence, they crave your understanding, and will respond enthusiastically to the least sign of it. Normal success, meeting customer expectations, means to improve the most outrageous and flagrant violations of their needs from version to version. They will likely stay with you if you are faithful about that, though they may well be sullen if not mutinous.  

   

Great software, however, requires that you pivot your entire technology so that it flows in the direction of their deepest needs. You must innovate in ways that clearly affirm their inarticulate desires. Surprise them by articulating and resolving in your product concerns and fantasies that heretofore had been rumbling about only in their pre-conscious. The fantasies of the market are generally centered on issues of empowerment, control and security. The market wants to be able to do things with its computers that it currently can&#39;t. Customers often find they can&#39;t even publicly admit these needs for fear of computer illiteracy. They derive value and security from being able to apply your software. To admit that they can&#39;t do what they want to do requires a sense of security beyond most customers’ reach.  

   

Market understanding is the foundation of great software. To repeatedly demonstrate through a series of two or three releases that you genuinely understand the market will result in enormous customer loyalty and brand equity. You will be viewed as the source of the market&#39;s empowerment. They will be rapturous.  

   

Gaining this understanding and embodying it in your software requires skill, tenacity and creativity. You must recognize the central market need and organize all your technology and communications efforts in the direction of satisfying that need. While good listening, careful observation and concept testing will be required for you to identify the correct need, addressing it in your product will have these effects:  

   

  1. It will appeal to the customer&#39;s sense of security.  

   

  2. It will extend the customer&#39;s control.  

   

  3. It will be such that if all else were dropped from your product, but the central need was met in unique ways, the product would be compelling.  

   

  4. It will clarify your product messages.  

   

  5. It will simplify your product&#39;s use.  

   

   

**14. Remember one thing: Unity.**  

   

Unity is the master principle of great software. Each element in the product is necessary to the value of the whole and all necessary elements are there. Since everything you need is there, you aren&#39;t tempted to go beyond the present experience, and since nothing is there that isn&#39;t required, your absorption into the world of the product will not be disturbed. Unity of purpose and unity in execution should be the hallmark of your team. Unity is achieved in a product by following certain creative principles (#15-#19, below), whether intuitively or consciously.  

   

**15. State your theme.**  

   

Theme is the dominant idea that constitutes the basis of the design. All of the values of the product must stem from the theme. In order for people to comprehend the theme, it must be rendered with surpassing clarity. Theme is analogous to purpose. The more specific the purpose, the greater the effect. Having a theme to the product will require that you eliminate or at least minimize orthogonal values. This is painful and involves risk.  

   

**16. Vary it.**  

   

Variation is the theme restated and elaborated in slightly altered and embroidered ways. Variation is the means by which we intensify the user&#39;s comprehension and appreciation of our theme, and leverage his/her growing consciousness in new ways.  

   

**17. Balance it.**  

   

Allocate appropriate emphasis among the various elements of the product. If a key component supporting the theme, encountered every time the thematic function is enacted, is weak, the theme is weakly stated and the product will be justly criticized.  

   

**18. Evolve it.**  

   

Evolution is when earlier parts determine later parts. Lessons learned in one part of the product apply to the others. Things progress in a way that is pleasing. Outcomes, if not predictable, are satisfying because the product foreshadows them in countless ways.  

   

**19. Your product should be a hierarchy.**  

   

Hierarchy is when the elements of the product gain attention in proportion to their importance. Closely related to the property of balance, hierarchy provides a means for establishing and evaluating balance. If the theme is the top of the hierarchy, elements at the next level have balanced value with respect to each other, all equally supporting the thematic function, and so on throughout the rest of the hierarchy.  

   

**20. Establish a shared vision.**  

   

It seems absurd to even have to state this, yet it is perhaps the most difficult thing of all to achieve. Everybody on the team must know what they are trying to achieve, what the finished product will look like, what the basis of the product strategy is, and when they must deliver it in order for it to have its intended effect. Contradictory visions must be resolved and unified. Harmonious purpose must be achieved, or greatness is out of the question and even shipping becomes infinitely more complicated.  

   

   


Shipping
  

   

**21. Get the team into ship mode.**  

   

There is a moment on every development project when it is ideal for a team to enter ship-mode. Ship mode is a high performance period characterized by efficiency and determination. It is a period of flow. Before a team can enter ship mode, several pre-requisites must be satisfied.  

   

  1. Shipment must be the next milestone.  

   

  2. Everybody (or nearly everybody) must believe that achieving the milestone is possible.  

   

  3. All members of the team must understand precisely what they must do prior to shipping. All unknowns are factored out.  

   

  4. Management must lead the team to ship mode by entering ship mode first. That is, superfluous management hoo-ha is eliminated, the manager’s awareness of detail climbs, fire-drills and other de-prioritizing activities are eliminated entirely and tremendous focus is brought to bear.  

   

  5. The team must desire to ship. Generally, a complete awareness of the effect of shipping (or not shipping) will create desire.  

   

The team becomes especially vigilant about thinking things through, and looking for traps. Check-ins are made with extra precaution. Stabilization of the product is the principle goal. All development is complete but for bug fixing.  

   

The endgame, the last stage of shipmode, is different yet again. It is conceptually a very simple exercise. There is a list of activities. When every activity on the list is complete, you ship. Though the list might have hundreds or thousands of items, it is still just a list. There is no time for any effort that does not contribute toward completing the items on the list. Everybody is expected to complete their items as promised. As unanticipated items arise, after appropriate resistance, they are put on the list.  

   

A daily meeting should be established, with final decision-makers in attendance. Agenda is ad hoc, assembled at the beginning of each meeting. No item is postponed that can be handled now. The team is aware that all issues can be brought to this meeting for expeditious remedy. Management is involved, leading the team toward their goal.  

   

The goal is an acceptable quality level at ship time. Only showstopper bugs should be addressed at all. Showstoppers are bugs that will either effect more than a handful of users or will cause unacceptably serious errors. Cosmetic changes, performance enhancements, new functions are not appropriate changes. The purpose of beta feedback during this period is to prove there are no showstoppers, provide advance warning of unanticipated market reaction and provide input to the next release.  

   

Understand the range of quality that is acceptable to your customers. How many low priority bugs did your product ship with last time? Was it a problem? Are the customers better off with this product including this bug? Since destabilizing the software is more of a problem than most bugs, be very careful about which bugs you fix. This is why we have &#34;ReadMe’s&#34; and bug lists.  

   

Shipmode is basically a succession of daily milestones climaxing with the product’s shipment.
