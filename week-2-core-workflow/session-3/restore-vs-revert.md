#COMPARISON BETWEEN git restore, git restore --staged, git revert, git reset --soft HEAD

|Command     |Change History    |Safe for Shared Repo?     |Typical Use Case|
|:----------- | :---------------------  |:-------------  |:---------------------| 
|*git restore* | Does nto change history  | Yes | Discarding unstaged changes|
|*git restore --staged* | Does not change history | Yes | Unstaging an accidentally staged file |
|*git revert* | Creates a new commit | Yes | Undoing an old commit after it has been pushed |
|*git reset --soft HEAD* | Erases a number of recent commits | No (Local only) | Completely wiping out recent commits and code changes|
 
                                                                
