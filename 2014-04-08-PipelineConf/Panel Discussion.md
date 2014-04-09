# Panel discussion

###On limitations of Continuous Delivery

  * Mobile apps are harder due to deploy gateway imposed by app stores
  * CD value is limited for legacy systems that rarely changes
  * Rate of change (specially UI) can be overwhelming to the user:
    * Facebook does it badly
    * Amazon does it nicely
    * How intrusive are the changes is a design exercise
    * Google mixes approaches
      * Pop-up explaining new features
      * User switches (gmail labs):
        * Target for both early and late adopters
        * Pull vs. Push of new features
    * Are user getting more used to frequent changes? (Windows vs mobile app updates)
    
### On role changes in Continuous Delivery

* CD requires some skills to be present in all roles
  * Testers can't just be UI testers (bottleneck)
* Less about roles within the team, more about team competences
* Sometimes is useful to bring outsiders from the same role but with experience in CD
* Who needs managers when there's no "schedule" (short value stream)?
  * General shift from projects to products
* Ops need to be able to automate

### How does "fake" Continous Delivery look like?

* Deploying fast by skipping verification (tests)
* Deploying fast with no traceability
* Faking won't be a problem because doing CD properly will soon become a competitive advantage (like Lean for japanese industry, Agile for software in general)
* Creating a deployment pipeline but keeping the same cycle time of weeks/months
* Long lived feature branches
* Manual regression testing
* No feedback to the business
  * Broken feedback loop ("open loop continous delivery")

### Overcoming organisational barriers for Continous Delivery

* Sell its benefits
* Business change/transformation literature instead of tech
  * Doing it all organically is a myth
  * Take the IT director for a stake lunch
  * Follow the resistance path
  * Get excuses out of the way
  * "People don't know what they want until you show it to them" (Steve jobs)
  * Be the friendly guy who challenges and break barriers
  * Tool first as a way to show what works (admit some vendors know more than you)


