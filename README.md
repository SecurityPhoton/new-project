This file contains instructions HOW TO work on new features without affecting the main branch.

1. On a local machine (after you have git installed) in local terminal (or git bash terminal on Windows) type:

git clone https://github.com/pontarr/new-project.git

and this will clone the repo to our local machine.

2. Change directory

cd new-project

3. Change branch to "development"

git checkout development

4. After this you can create and change files and you will not affect main brach. Use git add <files> and git commit comands to stage and coomit changes. Use 

git push origin development

to push changes back to github.