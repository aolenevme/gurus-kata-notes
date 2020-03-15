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
> **There is lack of good languages for multiprocessing.** That\`s why barbarians are at the gates. Since early 2000s, clock rates don\`t growth according the [Moore’s Law](https://en.wikipedia.org/wiki/Moore%27s_law).
> So the only way to increase computer power is to increase density of chips. But there are only few of languages that allow convenient multiprocessing programming. Probably, the best one is [Clojure](https://clojure.org/).
> But what will happen with other mainstream languages that don\`t support multicore regime? 
