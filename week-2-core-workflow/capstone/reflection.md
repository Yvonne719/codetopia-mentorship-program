#REFLECTION
**1. When should you use git restore?**  - You should use  git restore when you want to move an unstaged file to its last commit state.

**2. When should you use git restore --staged?**  - You should use got restore --staged when you want to unstage a file but still keep any  changes made to it.

**3. Why is git revert safer than rewriting history?**  - git revert is safer than rewriting history because using it keeps old commits and only moves forward by creating a new and correct commit.

**4. What is the difference between revert and reset?**  - Revert only adds a brand new commit but reset rolls the repository timeline back to the previoous commit.

**5. What mistake did you make and how did you recover?**  - I kept hitting a `fatal: pathspec did not match any files` error because I was running `git add` from the wrong folder level. I realised and moved
into the correct folder.

**6. What did you learn during week 2?**  - During week 2, I learnt how to work around with commits, how to amend them, how to play aaround with my commit history and thanks to that knowledge, I was able to 
complete a school assignment that required the use of git and GitHHub. 
