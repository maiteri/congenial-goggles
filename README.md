This is my readme file
esentially while creating a blank remote repo you can connect it to a local directory and push all contents in that directory to your remote repo
this read me file started on my laptop and is about to move to my remote repo
by using the git init we create en empty git repo and add the read me file by using the git add cmd which stages/ prepares the file which is now being tracked by git.
git commit using the -m flag creates a commit on the local repo, this allows us to push it now to the remote repo created earlier namely congenial_goggles
we create the path from our local to the remote repo. we create a short name for our repo path in this case origin. this will point this directory to our remote. we can use the short name origin in other directories too to point paths.
this cmd baptizes the path as origin - git remote add origin "copied remote ssh url"
git push -u origin main sends our code to the remote repo on git. the -u flag tells git to save the remote repo as the default push destination for the current branch.hereafter git push will suffice