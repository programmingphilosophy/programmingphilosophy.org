---
title: "The Twelve-Factor App"
author: "Jade Meskill"
date: 2015-02-02T00:00:00Z
lastmod: 2019-04-26T11:54:30-07:00
draft: false

---

I was talking to a friend of mine this week and he pointed me to something I&#39;d never heard of before. The Twelve-Factor App from Heroku. I will share the core of the philosophy and the 12 factors, but I encourage you to read them in detail at [http://12factor.net/](http://12factor.net/). Lots of great takeaways here.  

From The Introduction:  

In the modern era, software is commonly delivered as a service: called web apps, or software-as-a-service. The twelve-factor app is a methodology for building software-as-a-service apps that:  

 * Use **declarative** formats for setup automation, to minimize time and cost for new developers joining the project;  

 * Have a **clean contract** with the underlying operating system, offering **maximum portability** between execution environments;  

 * Are suitable for **deployment** on modern **cloud platforms**, obviating the need for servers and systems administration;  

 * **Minimize divergence** between development and production, enabling **continuous deployment** for maximum agility;  

 * And can **scale up** without significant changes to tooling, architecture, or development practices.  

The twelve-factor methodology can be applied to apps written in any programming language, and which use any combination of backing services (database, queue, memory cache, etc).  

The Twelve Factors  

**I. Codebase**  

  One codebase tracked in revision control, many deploys  

**II. Dependencies**  

  Explicitly declare and isolate dependencies  

**III. Config**  

  Store config in the environment  

**IV. Backing Services**  

  Treat backing services as attached resources  

**V. Build, release, run**  

  Strictly separate build and run stages  

**VI. Processes**  

  Execute the app as one or more stateless processes  

**VII. Port binding**  

  Export services via port binding  

**VIII. Concurrency**  

  Scale out via the process model  

**IX. Disposability**  

  Maximize robustness with fast startup and graceful shutdown  

**X. Dev/prod parity**  

  Keep development, staging, and production as similar as possible  

**XI. Logs**  

  Treat logs as event streams  

**XII. Admin processes**  

  Run admin/management tasks as one-off processes
