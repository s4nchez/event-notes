# Process Echoes in Code

* Michael Feathers (@mfeathers)
* Legacy Code
* Version Control
  * Ability to rollback
  * Ability to maintain multiple versions
    * Allow both rollback or fix
  * (Expensive) Insurance policy -> changelog
  * Analysis tool
  * Commit -> Method Events (added/deleted/updated)
* Intuition
  * "Better off adding more methods instead of updating existing ones"
* For how long have we been increasing the complexity of that code?
  * "When are we more likely to introduce bugs?"
* Proposal
  * Anonymous repository for project metrics
  * Normalising commits (file-by-file vs multi-file commits)
    * by day (probably better) vs. by commit
* Find "hot areas" of the code base (and how they change over time)
* Find "classes that tend to change at the same time"
* Can we infer the real history of a project by just looking at its changelog?
* Presence of test vs. refactoring