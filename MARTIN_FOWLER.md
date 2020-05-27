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
