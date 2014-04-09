#Big ideas, small company, moderate heresy

* Alex Wilson ([@pr0bablyfine](https://www.twitter.com/pr0bablyfine)) and Benji Webber ([@benjiweber](https://www.twitter.com/benjiweber))
* Unruly Media
* Team grew from 12 to 120 people in 2 years
* Short feedback loops:
  * Pairing: shortest feedback loop for code reviews
  * TDD
  * Customer on site
  * Push to deploy
  * Minimise value stream length (currently 2 hours)
* Work as a stream
  * No iteration planning
* No Continuous Integration
  * Developers deploy from their machines
  * Deploy on every push to github
  * Heavy usage of feature toggles
  * No need for branching
* Team structure
  * Siloing is bad
  * Teams are mostly developer focused
  * No "handovers"
  * No predefined teams
  * Specialists tend to act more as consultants (pairing)
  * Collective Ownership not just for code (tests/operations)
* Infrastructure challenges
  * 1 to 1000 servers
  * Making servers disposable
    * AWS machines can disappear without notice
    * Continously disposing servers to make sure everything works fine
  * New projects have to be deployed on first day (walking skeleton)
  * Acceptance Test Driven Infrastructure
  * Shared infrastructure
    * Assumed care, ensured suffering
    * Crossteam collaboration (squads)
  * Try to keep systems homogenious for easier handling
* Development scaling challenges
  * Product boundaries
  * Split teams on demand
  * Deployment speeds
  * Cross polination of knowledge
  * Collective ownership vs. freedom to try new technologies
* Use a gateway analogy instead of pipeline
  
  