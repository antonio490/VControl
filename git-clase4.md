# Using Github to collaborate

In order to post all my local commits I have to use the command
<kbd>git push</kbd> 

- Create a new repository
- Initialize the repository with a README (optional)
- Type <kbd> git remote </kbd> to see if there is already a remote repository.
- git remote add origin git@github.com:antonio490/version-control.git
- Type <kbd> git push origin master</kbd> to add our local repository into Github

### Editing files on Github

What happens if we make a commit on our github repository??
We have to update our local repository since it is not present.

<kbd> git pull origin master </kbd>

### Forking a repository

It is possible to clone a repository from someone else and push our changes without affecting the original copy. Forking allow us to do this and also to give recognition to the author from the original repository.