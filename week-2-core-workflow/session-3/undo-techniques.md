#DOCUMENTATION FOR undo-techniques.md file

**Commands to document**
* git restore
* git restore --staged
* git revert
* git reset --soft

**1. git restore**
* *Purpose* - To completely discard unstaged changes made to a file and bing it back to how it 
looked exactly the last time git saved it.

* *When to use it* - When you want to throw away the recent edits you've made to a file, maybe
because it has been messed up.

* *Example command* - git restore undo-tecniques.md

* *Expected result* - The undo-tecniques.md file goes back to its last saved, discarding the recent
edits made to it.


**2. git restore --staged**
* *Purpose* - To remove a file from the staging area without changing or deleting the actual file.

* *When to use it* - When you've accidentally ran git add on a file and you do not want to commit
it just yet

* *Example command* - git restore --staged restore-vs-revert.md

* *Expected result* - The file name changes from green to red when yu ran git status

**3. git revert** 
* *Purpose* - To undo an old, already-committed mistake by creating a brand new commit that does
the exact opposite of the bad commit

* *When to use  it* - When you've already committed a change to your git history but you realise
need to change something about your project without deleting past project history

* *Example command* - git revert 3fc4ff0

* *Expected result* - Git creates a new commit that reverses the changes of the bad commit while
leaving your entire history timeline intact

**4. git reset --soft**
* *Purpose* - To undo the number of last commits you specified while keeping changes made still
staged.

* *When to use it* - When you committed your work but realised that you need to make changes to
your commit message or maybe need to add additional files.

* *Example command* - git reset --soft HEAD~3

* *Expected result* - The last 3 commitis disappear from your history, but all your hardwork is
preserved and stays green in the staging area so you can fix it and commit it again








