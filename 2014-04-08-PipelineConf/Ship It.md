#Ship it!

* Phil Wills ([@philwills](http://www.twitter.com/philwills))
* Guardian
* Why?
  * Shorten cycle time
  * Changes are only taken seriously when in production
  * No big bangs = Smaller issues
    * Easier to find and fix
    * More confident about applying the fix
  * Deploying at 5pm on Fridays should be ok!
  * Less release planning overhead (just work on top priorities all the time)
* How?
  * Show it's possible:
    * 1 step deployment to Google App Code for a simple component
  * Get help from experienced people
* Tools
  * [https://github.com/guardian/deploy](https://github.com/guardian/deploy) 
  * AWS (specially Cloud Formation)
  * Monitoring dashboards
  * Feature toggles using HTTP header
* Costs
  * Relying on a Release Manager vs Automating?
  * New work vs revisiting old features frequently?
  * Deployments constrained by timezone
* Some deployments are still kicked manually
  * "Push the button" as team building exercise