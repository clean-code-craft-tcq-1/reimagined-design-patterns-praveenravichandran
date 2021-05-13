# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.
> 

Observer Pattern:
  Summary:
    Observer is the interesting pattern which will be useful on real time data tracking. Consider we need the live update of the score, then using this pattern we can easily get the updates when we subscribed to the score board system. Once subscribed it will provide the new data to all the subscribers.
  Advantages:
    Data will be in updated version always.
    Easy to use.
  Disadvantage:
    May cause memory leak if the subscription is not handled properly
    
Builder Pattern:
  Summary:
    Builder pattern can be used if you have a large number of properties to an object. Using this you can build each property as needed. We can take subway example, there are varieties of add on options available and it is not neccessary to add them all. For eg sub(olives, cheese, tomatos, onions) is more complex in simple you can say it as addOlives, addCheese, addTomatos this is what builder pattern does.
  Advantages:
    Reduced complexity
  Disadvantages:
    More lines of code
    
Adapter Pattern:
  Summary: 
    Adapter pattern as the name implies it has the quality to adapt and change the functionality as required. Consider there are muliple payment methods for credit card and debit card and each of them have separate gateways. Now using the adpater we can write our logic to build the response as needed.
  Advantages:
    More flexibility
    Loosely coupled
  Disadvantage:
    More number of adapter may need if we have different criterias
    
Proxy pattern:
  Summary:
    Proxy is the replacement or substitute of the actual object. We can take an example cricket here if the captain is out of the field for some reasons then the vice captain will be acting as a Proxy and take decisions when needed. Similarly whenever the object is needed of any response then the proxy object will be helpful to provide that response.
  Advantages:
    There will be immediate whenever its needed
    Availability is high
  Disadvantages:
    Response will not be right all the time
