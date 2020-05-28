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
