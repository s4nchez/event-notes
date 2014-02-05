# How Much Should I Refactor?

* Matt Wynne (@mattwynne)
* Cucumber codebase
* Refactoring
  * Business think refactoring == waste
  * Kitchen metaphor: you see the food, you should see the kitchen ;)
  * How much is enough?
    * You're probably not doing enough
    * Rule of thumb: "If you're in doubt, do more"
* Commit based analysis
* Assumptions
  1. If tests haven't changed in a commit, it's a refactor (~36% refactor)
  2. If contains "refactor" in the commit message, it's a refactor (jumped to ~48%)
  3. If the # of tests haven't changed in a commit, it's a refactor (jumped to ~76%)
* Metrics and the environment
  * "Toy problem" feeling
  * "Discovery mode" vs. "Clear goal"
  * Guilty vs. Proud feeling
  