# Uncle Bob's Blog
> https://blog.cleancoder.com/

## Articles
1. [What Software Craftsmanship is about](https://blog.cleancoder.com/uncle-bob/2011/01/17/software-craftsmanship-is-about.html)
> **We are tired of writing crap.** That`s why professionals try to create best designs. Write tests first. Test everything that can be tested. Practice to become better at the craft. 
> Go slow and steady in order to win the race. It is not because it is fashionable. No. Because it is the only one way to satisfy both customers, and business, and us, engineers.

2. [Bringing Balance to the Force](https://blog.cleancoder.com/uncle-bob/2011/01/19/individuals-and-interactions.html)
> **There is a "crevasse" between developers and managers in Agile.** Please, don`t ignore both technical topics and "manager" topics during work. Otherwise it widens the "crevasse".
> The people part is complicated. The technical part is complicated also. So congratulate your colleagues for their dedication to their discipline. Remember, these are your team-mates. 
> You want them to be able to play their positions with skill and professionalism. You want them to be good at their jobs. And, if you want them to respect your role, you must first respect theirs.

3. [Screaming Architecture](https://blog.cleancoder.com/uncle-bob/2011/09/30/Screaming-Architecture.html)
> **A good architecture emphasizes the use-cases and decouples them from peripheral concerns.** 
> The software architecture should scream about the use cases of the application, just as the plans for a house or a library scream about the use cases of those buildings.
> Your system architecture should be as ignorant as possible about how it is to be delivered, what frameworks, databases, web-servers to use. 
> View all these variables skeptically and know how to protect yourself from them. 
> If you do so, your code will be very flexible and testable in-situ, without any of the complications and additional infrastructure adjustments.

4. [Simple Hickey](https://blog.cleancoder.com/uncle-bob/2011/10/20/Simple-Hickey.html)
> **Just watch these videos: [Simple Made Easy](https://www.youtube.com/watch?v=oytL881p-nQ) and [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc&t=18s)
> by Rich Hickey 🤟🏻**

5. [Double Entry Bookkeeping Dilemma. Should I Invest or Not?](https://blog.cleancoder.com/uncle-bob/2011/11/06/Double-Entry-Bookkeeping-Dilemma-Should-I-Invest-or-Not.html)
> **Unit tests are necessary, but they may be misleading. There is a nice post: [Unit Testing Dilemma: Should I Invest or Not?](https://blogs.agilefaqs.com/2011/11/01/unit-testing-dilemma-should-i-invest-or-not/)**

6. [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2011/11/22/Clean-Architecture.html)
> **No matter how large any one part of the system is, the other parts should be decoupled from it.** This article is the continuation of [Screaming Architecture](https://blog.cleancoder.com/uncle-bob/2011/09/30/Screaming-Architecture.html)
> and answers to criticism:

> **First. It`s not a rocket science.** For example, you separate the UI from the business rules by passing simple data structures between the two. You don’t let your controllers know anything about the business rules. 
> Instead, the controllers unpack the HttpRequest object into a simple vanilla data structure, and then pass that data structure to an interactor object that implements the 
> use case by invoking business objects. The interactor then gathers the response data into another vanilla data structure and passes it back to the UI. The views do not know 
> about the business objects. They just look in that data structure and present the response.

> **Second. It won\`t slow you down.** Decoupling always speeds you up. It allows to defer decisions about other parts. It eases testing.

> **Third. It\`s not Big Up Front Design.** There is nothing wrong with spending a few hours or even a day or two, pondering the shape of your system in order to decouple it. 
> See: [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc&t=18s)

> **Fourth. These ideas are old.** They come from people like David Parnas, Tom Demarco, Grady Booch, Ivar Jacobson and many others.

7. [The Barbarians are at the Gates](https://blog.cleancoder.com/uncle-bob/2011/12/11/The-Barbarians-are-at-the-Gates.html)
> **There is lack of good languages for multiprocessing.** That\`s why barbarians are at the gates. Since early 2000s, clock rates don\`t grow according to [Moore’s Law](https://en.wikipedia.org/wiki/Moore%27s_law).
> So the only way to increase computer power is to increase density of chips. But there are only few languages that allow convenient multiprocessing. Probably, the best one is [Clojure](https://clojure.org/).
> But what will happen with other mainstream languages that don\`t support multicore regime? 

8. [Flipping the Bit](https://blog.cleancoder.com/uncle-bob/2012/01/11/Flipping-the-Bit.html)
> **I want you to believe that Test Driven Development saves time in every case and every situation without exception amen.** 
> Just flip that Bit in your head and experience that TDD is very beneficial. 

9. [The Letter](https://blog.cleancoder.com/uncle-bob/2012/01/12/The-Letter.html)
> **We need to become a self-regulating and self-policing profession.** Software is everywhere, from coffee machines to surgery robots. 
> Expectations are simply too high to allow developers to remain just hackers, heroics, and hermits.
> Be responsible until somebody will _make_ you so.

10. [Fecophiles](https://blog.cleancoder.com/uncle-bob/2012/01/20/Fecophiles.html)
> **Fecophiles. People who like to smell poop.** Or, probably, they just live in crap and don\`t smell it. 
> There are lots of fecophiles out there. They need to take a step back and inhale deeply through their noses.

11. [The Ruby Colored Box](https://blog.cleancoder.com/uncle-bob/2012/01/31/The-Ruby-Colored-Box.html)
> **You need real programmers when you hire people.** Don\`t worry if they don\`t know your language. They will know it in a month if they are experienced enough.
> During an interview ask them what they don\`t know and watch how they will act outside of the comfort zone.

12. [Service Oriented Agony](https://blog.cleancoder.com/uncle-bob/2012/02/01/Service-Oriented-Agony.html)
> **There are [SRP](https://en.wikipedia.org/wiki/Single-responsibility_principle) and its big brother [CCP](https://ericbackhage.net/clean-code/the-common-closure-principle/). There is violation of them.** When people group together things that change together, they occasionally group things that change for different reasons. This leads to a set of different problems that may slow down work. There are solutions:
  
> **First.** Sometimes it is better to avoid redundant decoupling and live within a single monolith.
  
> **Second.** The system needs to be partitioned into real business services by business rules.
  
> **Third.** If parts aren\`t business services then interfaces have to be generic so that every new feature doesn\`t require a change throughout the whole system.

13. [After the Disaster](https://blog.cleancoder.com/uncle-bob/2012/04/18/After-The-Disaster.html)
> **Soon _they_ will understand that IT industry is a swamp, but civilization significantly depends on it.** And then governments might start to regulate us. 
> They could turn us all into civil servants and do anything they want. And then life will be hell.

14. [Why is Estimating so Hard?](https://blog.cleancoder.com/uncle-bob/2012/04/20/Why-Is-Estimating-So-Hard.html)
> **"Tasks that appear easy for a human to solve are often described by complex procedures.** So when estimating, make sure you aren\`t affected by the apparent ease of that task. 
> Look below the surface to try to enumerate the number of procedural elements."

> "And if anyone tries to tell you that your estimate is bogus because the task is so simple, ask them to write down the procedure for tying their shoes."

15. [NO DB](https://blog.cleancoder.com/uncle-bob/2012/05/15/NODB.html)
> **The center of your application are the use cases of your application.** The database or used frameworks are just details that you don’t need to figure out right away.

> You determine your data model when all use cases and business rules are written and tested. By that time you will have identified all the queries, all the relationships, 
> all the data elements, and you’ll be able to construct a data model that fits nicely into a database.

16. [The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
> **Read it and read again!** This is impossible to shrink it. And I won\`t summarize the article anyhow. Probably, I\`m too biased, but everybody has to read it thoroughly, 
> think it over and make notes on their own. Amen.

17. [Functional Programming for the Object Oriented Programmer](https://blog.cleancoder.com/uncle-bob/2012/08/24/functional-programming-for-the-object-oriented-programmer.html)
> **[It\`s a good book to start with FP and Clojure at once.](https://leanpub.com/fp-oo)** What better way to explain and expose functional programming to an OO programmer than to build an object system in a functional language?

18. [The New CTO](https://blog.cleancoder.com/uncle-bob/2012/09/06/I-am-Your-New-CTO.html)
> **What CTOs expect from us:**
* QA will find nothing.
* We will cover for each other.
* We will make Honest Estimates.
* We will say ‘No’.
* We will not be afraid of our code.
* The only way to go fast is to go well.
* We will not ship shit.

19. [Three Paradigms](https://blog.cleancoder.com/uncle-bob/2012/12/19/Three-Paradigms.html)
> **Programming is the same as it was during the last 60 years.** There were and are just three paradigms: Structured Programming (1968), Object Oriented Programming (1966), 
> and Functional Programming (1957). There hasn\`t been a new paradigm; so perhaps that\`s a good indication that there aren\`t any more to find. Must we use all these paradigms, 
> or can we pick and choose? Probably, we should choose functional programming. Because functional programs don\`t use assignment, and therefore don\`t have side effects, and therefore 
> don\`t have concurrent update problems. You can read more here: [The Barbarians are at the Gates](https://blog.cleancoder.com/uncle-bob/2011/12/11/The-Barbarians-are-at-the-Gates.html)

20. [FP Basics E1](https://blog.cleancoder.com/uncle-bob/2012/12/22/FPBE1-Whats-it-all-about.html)
> **Functional programming is programming without assignment statements.** 

> **Referential Transparency** means that no function can have a side effect. That means that no variable, once initialized, can ever change its value; since assignment 
> is the quintessential side effect.

> **Hence**, if the value of a memory location, once initialized, does not change during the course of a program execution, then there’s nothing for
> processors to compete over. You can’t have concurrent update problems if you don’t update!

21. [Brave New Year](https://blog.cleancoder.com/uncle-bob/2012/12/29/Brave-New-Year.html)
> **Computers do not behave like humans.** They are not employing human-like thought. They do precisely what they have been programmed to do, no more - no less.
> If we see errors, we call them bugs. And they are fully our fault.

22. [FP Basics E2](https://blog.cleancoder.com/uncle-bob/2013/01/02/FPBE2-Whys-it-called-functional.html)
> **Functional language is a language that** has functions as first-class citizens (functions are treated as data elements that are manipulated no differently than integers or a characters), 
> enforces referential transparency by eliminating assignment, and maintains data history with persistent data structures.

23. [FP Basics E3](https://blog.cleancoder.com/uncle-bob/2013/01/07/FPBE3-Do-the-rules-change.html)
> **The old rules still apply.** Functional programming may be a change - an important change; but it doesn\`t change everything. Programming is still programming. 
> Discipline is still discipline. And TDD works just as well in functional programming as in any other style of programming.

24. [FP Basics E4](https://blog.cleancoder.com/uncle-bob/2013/01/29/FPBE4-Lazy-Evaluation.html)
> **Lazy sequences are really just a clever use of iterators.** When you have lazy sequences at your disposal, you can design your data structures for convenience,
> without undo concern for time and space.

25. [The Laborer and the Craftsman](https://blog.cleancoder.com/uncle-bob/2013/01/30/The-Craftsman-And-The-Laborer.html)
> **[The Manifesto for Software Craftsmanship](https://manifesto.softwarecraftsmanship.org/) 👨🏼‍🎓**

> **The most programmers are young**; and few have had the benefit of an experienced mentor. The result is that most programmers simply don’t know where the quality bar is. 
> They don’t know what disciplines they should adopt.

> **So there is nothing wrong with politely pointing out what you believe to be deficiencies in someone else’s code.** You don’t want to be rude or condescending when you do this; 
> but you do want to do it. How else can we learn unless someone points out where we’ve gone wrong? So please don’t let this event stop you from valid review and critique.

26. [The Humble Craftsman](https://blog.cleancoder.com/uncle-bob/2013/02/01/The-Humble-Craftsman.html)
> **What does it take to be a craftsman? It takes raising the bar.** It takes time. It takes experience. It takes mentoring. And, it takes a lot of trial and error. In our industry the best, and possibly the only, 
> way to refine your skill is to make lots and lots of mistakes; and to learn from others who have made lots and lots of mistakes. So thank goodness for those mistakes, and thank goodness
> for the people who made them. Without them, we’d have learned nothing. And especially thank the people who were willing to expose their mistakes to the world.

27. [The Principles of Craftsmanship](https://blog.cleancoder.com/uncle-bob/2013/02/10/ThePrinciplesOfCraftsmanship.html)
> **The principles of Software Craftsmanship according to [8th Light](https://8thlight.com/):**

> **Well-Crafted Software**
* We humbly demonstrate our expertise by delivering quality software.
    * We do not inflate our abilities or claim expertise where we have none.
* We continually master a variety of technologies and techniques.
    * We do not let unfamiliarity dissuade us from using the best tools.
* We take responsibility for the correctness of our code by testing it thoroughly.
    * We do not tolerate preventable defects.

> **Steadily Adding Value**
* We estimate with diligence.
    * We do not let fear or pressure make us promise what we can’t deliver.
* We always apply our best efforts to complete our work.
    * We do not make excuses.
* We work at a sustainable pace.
    * We do not burn out.

> **A Community of Professionals**
* We embrace differences of opinion and personality.
    * We do not allow our current practice to impede improvement.
* We prefer open source tools that we can inspect, evaluate, and improve.
    * We avoid proprietary products that lack transparency.
* We teach anyone with a willingness to learn.
    * We do not hoard our knowledge or practices.

> **Productive Partnerships**
* We show respect for our customers and fellow craftsmen.
    * We do not act unprofessionally or unethically.
* We communicate our progress honestly and openly with our customers.
    * We do not conceal or embellish.
* We partner with our customers to understand their business.
    * We do not propose solutions until we are sure we have found the right problem.

28. [The Start-Up Trap](https://blog.cleancoder.com/uncle-bob/2013/03/05/TheStartUpTrap.html)
> **The Start-Up trap is the thought that the start-up phase is different;** and that while you are in that phase success depends upon breaking the rules. This is stupid. 
> The start-up phase is not different. The start-up phase is simply the first of many phases, and it sets the tone for all those other phases. The disciplines that lead to 
> successful software are always valid, no matter what phase the company is in. It is laughable to think that good disciplines are less important during the start-up phase. 
> The truth is that, during the start-up phase, those disciplines are just as critical as they are at any other time.
  
> **Remember: The only way to go fast, is to go well.**

29. [The Pragmatics of TDD](https://blog.cleancoder.com/uncle-bob/2013/03/06/ThePragmaticsOfTDD.html)
> **Don\`t write any significant production code without making every effort to use TDD.**

> But sometimes you may not practice TDD strictly mainly because **code will be tested indirectly**:
* Don’t write tests for getters and setters.
* Don’t write tests for member variables.
* Don’t write tests for one line functions or trivial ones.
* Don’t write tests for GUIs. GUIs require fiddling. (_My remark: however, you can use [snapshot testing for GUI TDD](https://jestjs.io/docs/ru/snapshot-testing)_).
* Don’t write tests for frameworks, databases, web-servers, or other third-party software.

30. [An Open and Closed Case](https://blog.cleancoder.com/uncle-bob/2013/03/08/AnOpenAndClosedCase.html)
> **[Open-Closed principle](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle)**: You should be able to change the environment surrounding a module without changing the module itself.
