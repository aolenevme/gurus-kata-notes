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


31. [The Frenzied Panic of Rushing](https://blog.cleancoder.com/uncle-bob/2013/03/11/TheFrenziedPanicOfRushing.html)
> **Great code, that doesn\`t make or save money, isn\`t very interesting to businesses.**

> **Good disciplines don\`t slow you down.** Indeed _a discipline that slows you down is not a good discipline_. TDD is a good discipline.

> TDD does not take a two week MVP effort and turn it into nine months of auto-stimulation. Nor does refactoring. Nor does SOLID. Nor does pair programming.
> Nor does continuous integration. Nor do any of the other good disciplines out there.

> Getting done right does not mean getting done slow. Getting done right means getting done fast. You will go faster if you do things right. 
> You will go faster if you come down off the "high" generated by the illusion that effort is speed. You will go faster if you calm down, follow your disciplines, and refuse to rush.

32. [Fib. The T-P Premise.](https://blog.cleancoder.com/uncle-bob/2013/05/27/FibTPP.html)
> **Good news.** There may be different styles based on language type, but the vast majority of the low level coding decisions remain similar irrespective of those styles.

33. [Test First](https://blog.cleancoder.com/uncle-bob/2013/09/23/Test-first.html)
> **Just read this amazing article. Why? Because the tests are the most important component in the system. They are more important than the production code. And you are going to be convinced!** 
> We already know we should write them first; but we should also clean them first, maintain them first, think of them first, and keep them first. We should give our tests the highest priority.

34. [The Transformation Priority Premise](https://blog.cleancoder.com/uncle-bob/2013/05/27/TheTransformationPriorityPremise.html) and [Transformation Priority and Sorting](https://blog.cleancoder.com/uncle-bob/2013/05/27/TransformationPriorityAndSorting.html)
> **As the tests get more specific, the code gets more generic.**

> Learn how to write TDD properly following _The Transformation Priority Premise_: 
* ({}–>nil) _no code at all->code that employs nil_
* (nil->constant)
* (constant->constant+) _a simple constant to a more complex constant_
* (constant->scalar) _replacing a constant with a variable or an argument_
* (statement->statements) _adding more unconditional statements_
* (unconditional->if) _splitting the execution path_
* (scalar->array)
* (array->container)
* (statement->recursion)
* (if->while)
* (expression->function) _replacing an expression with a function or algorithm_
* (variable->assignment) _replacing the value of a variable_

35. [A.T. FAIL!](https://blog.cleancoder.com/uncle-bob/2013/09/26/AT-FAIL.html)
> **What causes systems to fail:**
> 1. The requirements are wrong;
> 2. The requirements are badly written;
> 3. The requirements are incomplete;
> 4. The programmers and the specifiers understand the requirements differently.
  
> **There are really just two solutions to these problems:**
> 1. Shorten the feedback loop between specification and execution using Agile;
> 2. Formalize the requirements writing [acceptance tests](https://cucumber.io/).

> **NB: The First Rule of Software Engineering: Don’t depend on things that change a lot!**

36. [Dance you Imps!](https://blog.cleancoder.com/uncle-bob/2013/10/01/Dance-You-Imps.html)
> **ORMs are data structure migrators. That’s all.** They move data from one place to another while making non-semantic changes to the form of that data. 
> They _do not_ create objects out of relational tables. Design your business objects without consideration for the relational schema. 
> Design your applications to _behave first_. Then figure out a way to bind those behaviors to the data brought into memory by your ORM.

37. [The Careless Ones](https://blog.cleancoder.com/uncle-bob/2013/10/24/The-Careless-Ones.html)
> **What kind of organization do you want to be associated with? One that cares? Or one that is careless.** And if you aren\`t in the right kind of organization, 
> what are you going to do about it?

38. [Healthcare.gov](https://blog.cleancoder.com/uncle-bob/2013/11/12/Healthcare-gov.html)
> **To what principles do we adhere?**

> **I will create software for the good of my users according to my ability and my judgement and never do harm to anyone.**

> **Professionalism is the willingness to refuse to obey orders that do harm to others.**

39. [Hordes Of Novices](https://blog.cleancoder.com/uncle-bob/2013/11/19/HoardsOfNovices.html)
> **Instead of hordes of novices, we need a small team of professionals.** Perhaps, we should rethink that strategy and hire one bard instead of hiring a million monkeys
> to write the script for Hamlet.

40. [Novices. A Coda](https://blog.cleancoder.com/uncle-bob/2013/11/25/Novices-Coda.html)
> **Our industry is young.** So we _don\`t need_ to throw masses of newly trained novices into mission critical projects without careful supervision, monitoring, and continuing education.
> We _don\`t need_ to expect novices to behave like professionals. We _don\`t need_ to continue in the absurd belief that a degree in computer science, or the completion of a boot camp, 
> is sufficient to produce a professional software developer.

41. [Extreme Programming, a Reflection](https://blog.cleancoder.com/uncle-bob/2013/12/10/Thankyou-Kent.html)
> **Nobody even thinks about Extreme Programming any more, we are all just trying to do it.**

> **Practices**:
* The Planning Game. _Scrum_.
* Small Releases. _Sprints and CI/CD_.
* Metaphor. _DDD_.
* Simple Design. _Keep the system as simple as possible at all times regardless of what we fear about in the future_.
* Testing. _TDD and Acceptance TDD_.
* Refactoring. _Always leave the code you`re editing a little better than you found it_.
* Pair Programming. _To be a team, programmers must regularly collaborate, at the keyboard_.
* Collective Ownership. _The code belongs to the team, not to the individual_.
* 40 Hour week. _Steady pace_.
* On Site Customer. _Someone from business who is responsible for requirements, must be readily and consistently available to the programming team_.
* Coding Standards. _Teams adopt a consistent and clean coding style_.

> **Stable Values**:
* Communication;
* Simplicity;
* Feedback;
* Courage.

42. [The Domain Discontinuity](https://blog.cleancoder.com/uncle-bob/2014/01/27/TheChickenOrTheRoad.html)
> **Restrict tests to operate through a small set of public methods.** Create tests that define _behaviours_, so _they are not coupled to the code_.

> **TDD can\`t even be begun until we know the architecture up front.** Because tests are a kind of _formal statement of requirements_. 
> So we can use TDD only to help us design a feature that lives within the architecture. Architecture and problem domain are _discontinuous_. 

> **But our up front decisions are limited to choosing a user experience, and choosing the architectural pattern that is most consistent with that user experience.** 
> Fortunately, the number of system architectures is relatively small: request/response systems (websites), event-driven applications (games), etc.

43. [The Domain Discontinuity](https://blog.cleancoder.com/uncle-bob/2014/01/27/TheChickenOrTheRoad.html)
> **Restrict tests to operate through a small set of public methods.** Create tests that define _behaviours_, so _they are not coupled to the code_.

> **TDD can\`t even be begun until we know the architecture up front.** Because tests are a kind of _formal statement of requirements_. 
> So we can use TDD only to help us design a feature that lives within the architecture. Architecture and problem domain are _discontinuous_. 

> **So our up front decisions are limited to choosing a user experience, and choosing the architectural pattern that is most consistent with that user experience.** 
> Fortunately, the number of system architectures is relatively small: request/response systems (websites), event-driven applications (games), etc.

44. [Where is the Foreman?](https://blog.cleancoder.com/uncle-bob/2014/02/21/WhereIsTheForeman.html)
> **If you want to get a project done, done right, and done on time, you need a foreman.** And that foreman has to be so technically astute that he can check the work of all the workers. 
> He has to be a guy with the commit rights. He has to make sure all the tests are written, and all the concerns are separated, and all the right dependencies are inverted. 
> He has to have the authority to reject any work he considers sub-standard. He has to have the power to say “No” to the unreasonable demands of the customers and managers. 
> Where is the Foreman?

45. [Oh Foreman, Where art Thou?](https://blog.cleancoder.com/uncle-bob/2014/02/23/OhForemanWhereArtThou.html)
> **The truth about teams is that teams only function well when there is a competent leader that holds the commit rights.** In a well functioning team the foreman allows everyone to commit, 
> and then simply, and silently, reviews the work. If someone does a great job, an attaboy is appropriate. If someone does a poor job, a private conversation, 
> followed by remedial action, is appropriate. In the normal case, everyone on the team can commit.

46. [A Spectrum of Trust](https://blog.cleancoder.com/uncle-bob/2014/02/27/TheTrustSpectrum.html)
> The perfect agile team is composed of 6-12 experienced developers with good design sense and a deep commitment to craftsmanship. 
> They all sit around a single table. They all start and end work at the same time. They all pair with each other 100% of the time; changing pair partners several times per day. 
> They have an on-site customer who perfectly balances the backlog. Their velocity is consistent and flat from iteration to iteration. They all practice TDD perfectly. 
> Their code coverage is 100%. They all refactor mercilessly. Their code is clean. They are the perfect agile team.
>
> **The open-source committer model (i.e. using foremen) has been shown very effective at achieving those ends.**

47. [When Should You Think?](https://blog.cleancoder.com/uncle-bob/2014/03/11/when-to-think.html)
> **Think before you code. Then think as you code. Then think after you code.** 
> Again, there is a nice video [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc&t=18s) by Rich Hickey.

48. [The True Corruption of Agile](https://blog.cleancoder.com/uncle-bob/2014/03/28/The-Corruption-of-Agile.html)
> **Agile is a culture expressed through a set of practices.** You can’t have a culture without practices; and the practices you follow identify your culture.

49. [Code Hoarders](https://blog.cleancoder.com/uncle-bob/2014/04/03/Code-Hoarders.html)
> **Is your work leaving a legacy of value, or are you just building a monstrous hoard for someone else to clean up?**
> Professionals make things better with time. The Legacy code left by professionals will be cleaner and cleaner the 
> older it is because it has enjoyed the long attention of those professionals.

50. [Monogamous TDD](https://blog.cleancoder.com/uncle-bob/2014/04/25/MonogamousTDD.html)
> **Why do we do TDD?**
* We spend less time debugging;
* The tests act as accurate, precise, and unambiguous documentation at the lowest level of the system;
* Writing tests first requires decoupling that other testing strategies do not; and we believe that such decoupling is beneficial;
* If you have a test suite that you trust so much that you are willing to deploy the system based solely on those tests passing; and if that test suite can be executed in seconds, or minutes, then you can quickly and easily clean the code without fear.

51. [When TDD doesn't work.](https://blog.cleancoder.com/uncle-bob/2014/04/30/When-tdd-does-not-work.html)
> **Remember the TDD rule: As the tests get more specific, the code gets more generic.**

> So there are areas where tests aren\`t appropriate:
* The physical boundary like CSS and HTML (but you can use snapshot testing anyway); 
* The layer just in front of that boundary that requires human interaction to fiddle with the results. Like config files;
* The support code for unit tests.

52. [Test Induced Design Damage?](https://blog.cleancoder.com/uncle-bob/2014/05/01/Design-Damage.html)
> **Programmers who “faithfully” practice TDD will create code that is “warped out of shape solely to accommodate testing objectives”.**

> **How do you separate concerns?** You separate behaviors that change at different times for different reasons. 
> Things that change together you keep together. Things that change apart you keep apart.

> GUIs change at a very different rate, and for very different reasons, than business rules. 
> Database schemas change for very different reasons, and at very different rates than business rules. 
> Keeping these concerns separate is _good design_.

53. [Professionalism and TDD (Reprise)](https://blog.cleancoder.com/uncle-bob/2014/05/02/ProfessionalismAndTDD.html)
> **Patients are dying out there! Our society as a whole is becoming more and more dependent on the software we produce; and the failures grow in significance with every passing year.**
> 
> If TDD is as significant to software as hand-washing was to medicine and is instrumental in pulling us back from the 
> brink of that looming catastrophe, then Kent Beck will be hailed a hero, and TDD will carry the full weight of professionalism. 
> After that, those who refuse to practice TDD will be excused from the ranks of professional programmers. It would not surprise me if, 
> one day, TDD had the force of law behind it.

54. [The Single Responsibility Principle](https://blog.cleancoder.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html)
> **The Single Responsibility Principle (SRP) states that each software module should have one and only one reason to change.**
> This principle is about people. It is people who request changes. And you don’t want to confuse those people, or yourself.
  
> When you write a software module, you want to make sure that when changes are requested, those changes can only originate from a 
> single person, or rather, a single tightly coupled group of people representing a single narrowly defined business function.

> This is the reason we do not put SQL in JSPs. This is the reason we do not generate HTML in the modules that compute results. 
> This is the reason that business rules should not know the database schema. This is the reason we separate concerns.

> **Gather together the things that change for the same reasons. Separate those things that change for different reasons.**

55. [When to Mock](https://blog.cleancoder.com/uncle-bob/2014/05/10/WhenToMock.html)
> **Mock across architecturally significant boundaries, but not within those boundaries.**
> It forces you to think through what your significant architectural boundaries are and to manage the dependencies across those boundaries 
> so that you can independently deploy (and develop) the components on either side of the boundary. 

> **Write your own mocks.**
> Writing your own mocks means you have to design your mocking structure. Plus, mocking across architectural boundaries is easy. And writing those mocks is trivial. 

56. [Framework Bound](https://blog.cleancoder.com/uncle-bob/2014/05/11/FrameworkBound.html)
> **Frameworks are written by people to solve certain problems that they have. Those problems may be similar to yours, but they are not yours.** You have different problems. 
> To the extent that your problems overlap, the framework can be enormously helpful. To the extent that your problems conflict, the framework can be a huge impediment.

> **Don\`t let those frameworks get too close.** They can touch peripheral subsystems; but keep them away from the core business logic. 
> The high level policies of systems shall never be touched by frameworks.

57. [The Open Closed Principle](https://blog.cleancoder.com/uncle-bob/2014/05/12/TheOpenClosedPrinciple.html)
> **You should be able to extend the behavior of a system without having to modify that system.** In other words, adding a new feature would involve leaving the old code in place
> and only deploying the new code like isolated features!

> Plugin systems are the apotheosis of the Open-Closed Principle. After all, the way you get a plugin architecture is to make sure that all dependencies 
> inside the plugin, point at the system; and that nothing in the system points out towards the plugins. The system doesn\`t know about the plugins. The plugins know about the system. 

> **When your fundamental business rules are the core of a plugin architecture, then you are never bound to a particular feature set, interface, database, framework, or anything else.**

58. [The Little Mocker](https://blog.cleancoder.com/uncle-bob/2014/05/14/TheLittleMocker.html)
> **Mostly use dummies, stubs, and spies. Write your own.** Don’t often use mocking tools. Otherwise you code may become extremely complicated.

59. [First](https://blog.cleancoder.com/uncle-bob/2014/05/19/First.html)
> **You’re not done until you also have tests for a piece of functionality.**

> **Documentation.** Well designed tests are small isolated snippets of code that call into the system being tested, expecting certain results. 
> A programmer can read the tests to understand what the tested code is supposed to do. So the tests are documents. 
> And they cannot get out of sync with the application.

> **Decoupling.** Well designed tests force a certain degree of decoupling. Often that decoupling is beneficial to the design of the system.

> **Confidence.** A well designed test suite with a high degree of coverage eliminates, or at least strongly mitigates the fear of change. 
> And when you aren’t afraid to change your code, you will clean it. And if you clean it, it won’t rot. And if it doesn’t rot, then the software team can go fast.

60. [Is TDD Dead? Final Thoughts about Teams.](https://blog.cleancoder.com/uncle-bob/2014/06/17/IsTddDeadFinalThoughts.html)
> **High-functioning teams must have a shared set of values.** Teams that don’t enjoy a shared set of values are unstable. 
> If each member of the team does what is right in their own eyes, without considering the values of the team; 
> then they don’t actually comprise a team. Instead they will behave chaotically, and work at cross purposes to each other.

61. [My Lawn](https://blog.cleancoder.com/uncle-bob/2014/06/20/MyLawn.html)
> **The older the programmer, the more questions the programmer can answer – and can take the time to answer.** 
> The implication is that older programmers are less rushed because they have more knowledge and skill. 
> Code doesn’t have to pour out of all their orifices because they can solve problems calmly, quickly, 
> and easily with much less code.

62. [A Little About Patterns](https://blog.cleancoder.com/uncle-bob/2014/06/30/ALittleAboutPatterns.html)
> **Design Patterns: Elements of Reusable Object-Oriented Software, by Eric Gamma, Richard Helm, Ralph Johnson, and John Vlissides.**

> The ideas aren’t glitter. The frameworks are. Most of the ideas in those frameworks are old. They’ve been around for decades. The ideas are … Design Patterns.

63. [Test Time](https://blog.cleancoder.com/uncle-bob/2014/09/03/TestTime.html)
> **Programmers who care about their systems, care about the tests for those systems.** Programmers who care about the tests, 
> make sure those tests run fast. Slow running tests represent a design flaw that reflects on the experience and professionalism 
> of the team. A slow running test suite is either a freshman error, or just plain carelessness.

64. [The More Things Change...](https://blog.cleancoder.com/uncle-bob/2014/09/18/TheMoreThingsChange.html)
> **The more things change, the more they stay the same.**

65. [Microservices and Jars](https://blog.cleancoder.com/uncle-bob/2014/09/19/MicroServicesAndJars.html)
> **Don’t leap into microservices just because it sounds cool.** One thing you lose is time. It takes time to communicate through a socket. 
> It takes time to decode REST messages. Try instead to segregate the system into jars using a plugin architecture first. 
> If that’s not sufficient, then consider introducing service boundaries at strategic points.

66. [Clean Micro-service Architecture](https://blog.cleancoder.com/uncle-bob/2014/10/01/CleanMicroserviceArchitecture.html)
> **Micro-services are a deployment option, not an architecture.** Like all options, a good architect keeps them open for as long as possible. 
> A good architect defers the decision about how the system will be deployed until the last responsible moment.  

> But if you can only deploy your system with micro-services, then you have coupled your architecture to that particular deployment model. 
> Indeed a system with a good Clean Architecture does not know which deployment option it is using.

67. [The Obligation of the Programmer.](https://blog.cleancoder.com/uncle-bob/2014/11/15/WeRuleTheWorld.html)
> **Order of the Programmer**
~~~
I am a computer programmer, I take deep pride in my profession. To it I owe solemn obligations.

All human progress has been spurred by the genius of those who manipulate information.

By making it possible to manipulate vastly more information than ever before, programmers have created enormous benefits 
for human society and greatly accelerated human progress. Were it not for the accumulated knowledge and experience of 
those programmers, mathematicians, and engineers who came before me, my efforts would be feeble.

As a programmer, I pledge to practice integrity and fair dealing, tolerance, and respect, and to uphold devotion to the 
standards and the dignity of my profession, conscious always that my skill carries with it the obligation to serve 
humanity by making the best use of the precious resources under our stewardship.

As a programmer, in humility and with the need for guidance, I shall participate in none but honest enterprises.
When needed, my skill and knowledge shall be given without reservation for the public good.
In the performance of duty and in fidelity to my profession, I shall give the utmost.
~~~

68. [Thorns around the Gold](https://blog.cleancoder.com/uncle-bob/2014/11/19/GoingForTheGold.html)
> **Write as many tests as you can that ignore the core functionality and deal instead with exceptional, degenerate, and ancillary behaviors.** 
> In that order, one by one:

> **Exceptional Behaviors.**
> These are behaviors that detect invalid inputs that the core functionality should never see. 
> These behaviors return error codes, log error messages, and/or throw exceptions.

> **Degenerate Behaviors.** These are inputs that cause the core functionality to do “nothing”.

> **Ancillary Behaviors.** The thing about ancillary behaviors is that they frequently turn out 
> to be useful to the core functionality in some in-obvious way. For example, it turns out that 
> the size of a stack is the array index used for push and pop operations in fixed-length stacks.

69. [OO vs FP](https://blog.cleancoder.com/uncle-bob/2014/11/24/FPvsOO.html)
> **OO is not about state.** Objects are bags of functions, not bags of data.

> **Functional Programs, like OO Programs, are composed of functions that operate on data.** 
> There is not much difference between f(o), o.f(), and (f o).

> _But..._

> **FP imposes discipline upon assignment.** You cannot change the state of a variable.

> **OO imposes discipline on function pointers.** What OO really comes down to is that 
> OO languages replace function pointers with convenient polymorphism.

> **Do both.** OO programming is good, when you know what it is. Functional programming 
> is good when you know what it is. And functional OO programming is also good once you know what it is.

70. [The Cycles of TDD](https://blog.cleancoder.com/uncle-bob/2014/12/17/TheCyclesOfTDD.html)
> **Second-by-Second nano-cycle. The Three Laws of TDD.**
~~~
1. You must write a failing test before you write any production code.
2. You must not write more of a test than is sufficient to fail, or fail to compile.
3. You must not write more production code than is sufficient to make the currently failing test pass.
~~~

> **Minute-by-Minute micro-cycle. Red-Green-Refactor.**
~~~
1. Create a unit tests that fails
2. Write production code that makes that test pass.
3. Clean up the mess you just made.
~~~

> **Decaminute-by-Decaminute milli-cycle. Specific/Generic.**
~~~
As the tests get more specific, the code gets more generic.
This is the cycle in which we apply the Transformation Priority Premise. 
We look for the symptoms of over-specificity by checking the kinds of production code we have written.
~~~

> **Hour-by-Hour. Primary Cycle. Boundaries.**
~~~
Every hour or so we stop and look at the overall system. We hunt for boundaries that we want to control. 
We make decisions about where to draw those boundaries, and which side of those boundaries our current 
activities should be constrained to. 
~~~

71. [The MODE-B Imperative](https://blog.cleancoder.com/uncle-bob/2015/02/21/ModeBImperative.html)
> **Why do so many programmers still work in a way that they pile mess upon mess, and framework upon a framework, 
> until their loop time grows from seconds to minutes and longer?** They inject so many dependencies that the builds 
> become fragile and error-prone. They create so many unisolated external dependencies that they might as well be 
> using paper tape. Why would anybody do anything that increased their loop time? Why wouldn’t everyone defend their
> loop time with their lives?

72. [Does Organization Matter?](https://blog.cleancoder.com/uncle-bob/2015/04/15/DoesOrganizationMatter.html)
> **Relatively simple things can tolerate a certain level of disorganization. However, as complexity increases, disorganization becomes suicidal.** 
