# GameChat
Clone your personal repository from the command line. You can also copy the command directly from your empty repository. Look under Working with your repository.
From a terminal window, run these commands

1.For cloning the files


git clone http://<username>@<Bitbucket Server URL>/scm/<project key>/website.git
Click for an explanation of these commands...
This creates an empty Git repository named TISwebsite

Add the files to your personal repository from the command line.
From a terminal window

cd existing-project

git init

git add --all
git commit -m "Initial Commit"
git remote add origin http://<Bitbucket Server URL>/scm/tis/website.git
git push -u origin master
