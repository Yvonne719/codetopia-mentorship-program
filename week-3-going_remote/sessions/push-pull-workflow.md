Document:
git remote add origin
git push -u origin main
git pull origin main
For each command explain:
● Purpose
● Syntax
● Example
● Expected outcome


#git remote add origin
*Purpose* - To link your local repo to your remote repo
*Syntax* git remote add origin <URL>
*Example* - git remote add origin https://github.com/Yvonne719/codetopia-mentorship-program.git
*Expected outcome* - Local git saves the link. Can be verified using git remote -v

#git push -u origin main
*Purpose* - To upload commits from your local repo to your remote repo. -u sets a tracking line 
between your local main and your remote main and can be ignored in your future pushes.
*Syntax* - git push -u origin <branch name(in this case, "main">
*Example* - git push origin main
*Expected outcome* - Copies of files from your local repo get uploaded to your remote repo and
the terminal shows a success message that a new brach tracking relation has been established.

#git pull origin main
*Purpose* - To sync changes made on your remote repo with your local repo.
*Syntax* - git pull origin <branch name>
*Example* - git pull origin main
*Expected outcome* - The terminal will show the files pulled down with the number of lines that were
added or changed. It also shows that it unpacked objects.
