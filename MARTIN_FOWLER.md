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
