## Affordance

"Quality of an object or environment that allows an individual to perform an action" (Don Norman)

* Nat Pryce (@npryce) and Giovanni Asproni (@gasproni)
* Rely more on the type system rather than write more tests?
* Actual vs. Perceived affordance (easier to guess?)
  * Naming convention
  * Language convention
  * Short functions
  * Common, consistent language
  * Metaphor (shared language)
  * Domain Types
  * Repeated exposure
  * e.g. teaching English as second language
* Harder to test code by convention
  * Null pointers far from the origin
  * Naming types as patterns (attracts junk over time)
    * CustomerService -> AddressBook
    * Understanding about the design pattern (e.g. builders)
    * FactoryFactory?
    * Visitors which are actually iterators
    * Inconsistencies
* Bad style you are familiar with does offer perceived affordance
  * affordance (consistency) or actual affordance (globals?)
* Method aliasing in ruby (map = collect) -> more expressive
* Cognitive dissonance of english words and the actual pattern
  * Factory (OOP) = good (I think I know what it means); 
  * Monad (FP) = bad (WTF is this? I have to learn!)
* Frameworks are double edged swords
  * Support specific affordance and many actually gets in the way
  * Affordance barriers
    * Doesn't do (don't know how it does)
    * Does it in unexpected ways
* Domain terms instead of patterns
  * BookRepository -> Bookshelf? (new metaphor)
  * May generate misuse (e.g. use cable as a whip)
* Can TDD make most important affordances visible?
* Exploratory aspect -> black + white box
* How to build objects
  * good vs. bad feedback
  