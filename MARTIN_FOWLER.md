# Martin Fowler's Blog
> https://martinfowler.com

1. [APIs should not be copyrightable](https://martinfowler.com/articles/copyright-api.html)
> **APIs should not be copyrightable.** You should be able to copyright a software component, but not its interface.
> So that programmers can reimplement its interface with another implementation to support: interoperability, 
> testing and competition.

2. [AccessModifier](https://martinfowler.com/bliki/AccessModifier.html)
> **Access control does not control access** If you have a field that's private it means no other class can get at it.
> Wrong! If you really want to you can subvert the access control mechanisms in almost any language. Usually the way 
> through is via reflection. The rationale is that debuggers and other system tools often need to see private data, 
> so usually the reflection interfaces allow you to do this.

3. [DDD_Aggregate](https://martinfowler.com/bliki/DDD_Aggregate.html)
> **A DDD aggregate is a cluster of domain objects that can be treated as a single unit.** An example may be an order and 
> its line-items, these will be separate objects, but it's useful to treat the order (together with its line items) as 
> a single aggregate.

> An aggregate will have one of its component objects be the aggregate root. Any references from outside the aggregate 
> should only go to the aggregate root. The root can thus ensure the integrity of the aggregate as a whole.
  
> Aggregates are the basic element of transfer of data storage - you request to load or save whole aggregates. 
> Transactions should not cross aggregate boundaries.

4. [Agile Brazil Interview](https://www.infoq.com/interviews/fowler-caroli-continuous-deployment/)
> **What to do when acceptance tests take a lot of time?** We have two layers of test. First layer is a fast moving set 
> of unit tests that gives you a quick feedback. Then, you have the acceptance tests that do run through the browser 
> that do have things like databases connected, running on a separate stage of the pipeline. Also you can run your 
> acceptance tests in parallel. Of course, their correct execution depends on the power of machines and there is no 
> dependency of one test on the other.

> **What would be a short time for build to have the feedback?** For the commit stage, you want 10 minutes or less.

> **Polyglot programming. What do you think about it?** The idea of using different languages for different strengths,
> that’s what polyglot programming is about. There is a separate point. I think the pragmatic programmers advice try 
> to learn a new different language (if you already know Java, learning C# doesn’t count) every year and not necessarily
> a language that you expect to use day-to-day in your production programming work, but one that will stretch your mind 
> in a different direction, open new possibilities.

> **How early and how continuously should we deliver?** As early as possible, but always the top quality. You want to go into 
> production, as rapidly as you possibly can and then you want to be cycling updates as quickly as you can, as well. 
> There is still attenuation here from how rapidly the customer wants to get something, wants the minimal thing that
> they can go with first.

5. [AgileImposition](https://martinfowler.com/bliki/AgileImposition.html)
> **As a methodology or design approach becomes fashionable, then we see a lot of people using it, or teaching it, who are 
> focusing on the fashion rather than the real details.** This can lead to reports of things done in agile's name which
> are a polar opposite to the principles of movement's founders. For example, imposing a process on a team is completely
> opposed to the principles of agile software, and has been since its inception.

6. [An Appropriate Use of Metrics](https://martinfowler.com/articles/useOfMetrics.html)
> **Metrics cannot be used as a substitute for thinking. So organizations must be vigilant against the undesirable 
> behaviors that emerge due to the inappropriate use of metrics.**

> **Guidelines for a more appropriate use of metrics:**
* **Explicitly link metrics to goals.** Management is responsible for ensuring the end goal is always kept in sight, working with the people with the most knowledge of the system to come up with measures that make the most sense to monitor for progress.
* **Favor tracking trends over absolute numbers.** Focusing on trends is important because it provides feedback based on real data on any change implemented and creates more options for organizations to react.
* **Use shorter tracking periods.** Organizations benefit from using shorter tracking periods as it creates more opportunities for re-planning that allows maximum value.
* **Change metrics when they stop driving change.** Organizations need to drop metrics that are no longer relevant.

7. [AbundantMutation](https://martinfowler.com/bliki/AbundantMutation.html)
> **Evolutionary Design expects the team to modify the design as the project proceeds; both to cope with requirements 
> changes and to take advantage of learning.** But evolutionary design requires attention, skill, and leadership. It's just 
> a different sort of leadership than many commonly think.


8. [ActivityOriented](https://martinfowler.com/bliki/ActivityOriented.html) and [OutcomeOriented](https://martinfowler.com/bliki/OutcomeOriented.html)
> **A mandate to deliver a business outcome is very different from a mandate to deliver a certain amount of scope. Scope delivery is easy, relatively speaking.** Outcome realization requires real collaboration between those who understand the problem and those who can fashion various levels of solution for it. Initial attempts at solution lead to a better understanding of the problem which leads to further attempts at better solutions. This doesn’t work where the product management organization is separate from the development (scope-delivery) organization.

> Outcome-oriented teams are necessarily cross-functional (multidisciplinary) whereas ActivityOriented teams are typically mono-functional (single specialty). In the most traditional scenario, an outcome might simply be defined in terms of a project. The project is funded on the basis of a business case and therefore the desired outcome is to realize what is promised in the business case. However, depending on the size of the project it may be organized as one or more teams. When these teams are set up along activity boundaries it becomes an activity-oriented project (or program) organization. On the other hand, we achieve an outcome-oriented organization by dividing the overall outcome into sub-outcomes and assigning sub-outcomes to cross-functional teams that are self-sufficient in terms of people required to deliver the sub-outcome.

9. [AgileVersusLean](https://martinfowler.com/bliki/AgileVersusLean.html)
> **Lean and agile are deeply intertwined in the software world. You can't really talk about them being alternatives, if you are doing agile you are doing lean and vice-versa.** Agile was always meant as a very broad concept, a core set of values and principles that was shared by processes that look superficially different. You don't do agile or lean you do agile and lean. The only question is how explicitly you use ideas that draw directly from lean manufacturing. Think of lean as a strand of thinking within the agile community, like a pattern.

10. [AgileHandover](https://martinfowler.com/bliki/AgileHandover.html)
> **Processes that produce mandatory documentation often produce stuff that isn't very helpful, and under the pressure of deadlines tends not to be kept up to date.** In many ways the agile approach is a preference for a smaller amount of higher quality documentation.

> Agile projects prefer face-to-face communication, so a common approach is to bring in members of a support/maintenance team to work with the development team for a while before they depart. By spending some time with both teams present, the development team could teach the system to the maintenance team as they are working the system.

11. [An example of preparatory refactoring](https://martinfowler.com/articles/preparatory-refactoring-example.html)
> ["For each desired change, make the change easy (warning: this may be hard), then make the easy change" - Kent Beck](https://twitter.com/KentBeck/status/250733358307500032?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E250733358307500032&ref_url=https%3A%2F%2Fmartinfowler.com%2Farticles%2Fpreparatory-refactoring-example.html)

12. [ApplicationBoundary](https://martinfowler.com/bliki/ApplicationBoundary.html)
> **Unfortunately, the boundaries of a piece of software are drawn primarily by human inter-relationships and politics rather than technical and functional considerations.** It's our nature to group things together and organize groups of people around these groups. If we are interested in thinking further about applications and how they interrelate, we should take a look at the strategic design section of [Domain-Driven Design](https://www.amazon.com/gp/product/0321125215?ie=UTF8&tag=martinfowlerc-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0321125215).

13. [AssertionFreeTesting](https://martinfowler.com/bliki/AssertionFreeTesting.html)
> **You have to be careful on interpreting code coverage data.**

14. [AvoidingRepetition](https://martinfowler.com/ieeeSoftware/repetition.pdf)
> **Don\`t repeat yourself. Say anything in your program only once. Design patterns help with it.** But as many people know, one of the problems with people who have just read a pattern is that they insist on using it, which often leads to more complicated designs. When you insist on using a pattern, ask, “What repetition is this removing?” Removing repetition makes it more likely that you’re making good use of the pattern. If not, perhaps you shouldn’t use it. 

15. [BeckDesignRules](https://martinfowler.com/bliki/BeckDesignRules.html)
* **Passes the tests**. It is the first and the most important one.
* **Reveals intention** (every intention is understandable) and **No Duplication** (DRY, or SPOT, or everything should be said "Once and only Once."). These are the second priority.
* **Fewest elements** (anything that doesn't serve the three prior rules should be removed). The last one in the priority order.

> P.S. It is the good rules to use during the code review.

16. [BeyondSoftwareArchitecture](https://martinfowler.com/books/hohmann.html)
> **Consider the book [Beyond Software Architecture](https://www.amazon.com/Beyond-Software-Architecture-Sustaining-Solutions/dp/0201775948).** Such things as the marketing view of a system, licensing terms, branding, deployment, billing. All of these issues have important technical and business implications. Senior technical people need to think about this stuff, or otherwise a technically capable system could fail to be good business decision.

17. [BlueGreenDeployment](https://martinfowler.com/bliki/BlueGreenDeployment.html)
> **The idea is about two environments, Blue and Green, that need to be different but as identical as possible.** You test new release on the Green environment. If everything is OK, you switch the router to the Green environment. In case of emeregency, you can use the Blue one as a rollback. When new release is coming up, you test it on the Blue environment. Then you switch the router again and use the Green environment as a preproduction. And then repeat. And repeat. Consider [this book for more insights](https://martinfowler.com/books/continuousDelivery.html).

18. [BroadStackTest](https://martinfowler.com/bliki/BroadStackTest.html)
> **Broad-stack tests have the advantage of exercising the application with all its parts connected together and thus can find bugs in the interaction between components in the way that unit tests cannot.** However broad-stack tests also tend to be harder to maintain and slower to run than unit tests. As a result the test pyramid suggests using fewer broad-stack tests. So before fixing a bug exposed by a broad-stack test, you should replicate the bug with a unit test. Then the unit test ensures the bug stays dead.

19. [Buildix](https://martinfowler.com/bliki/Buildix.html)
> **Getting a good CI/CD environment with all of things up and integrated together is a tougher job than you might think.** Inevitably you may find that you will be messing around for a week for any new project.

20. [Business Readable DSL](https://martinfowler.com/bliki/BusinessReadableDSL.html)
> **The idea is in making DSLs business-readable rather than business-writeable.** If business people are able to look at the DSL code and understand it, then we can build a deep and rich communication channel between software development and the underlying domain. The talent and the time involved to understand and build a program, is why programming has resisted being disintermediated for so long. It's also why many "non-programming" environments end up breeding their own class of programmers-in-fact.

21. [CanaryRelease](https://martinfowler.com/bliki/CanaryRelease.html)
> **Canary release is an incremental approach in rollout when you test new release on 1%, then on 10%, and then on 100% of users. Also it fits well with the A/B testing.**
