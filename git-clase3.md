# Git version control

> Antonio Sanz - Clase 3 "Creating and Modifying a repository"

### Creating a new repository

<kbd>git init</kbd>

<kbd>git status</kbd>

### Staging area

<kbd>git add</kbd>

When files are add from our working area, they move into a staging area in between.

-- Changes to be commited
    
    new file: cake-recipe.txt
    new file: frosting-recipe.txt

-- untracked files:
    
    chili-recipe.txt

### Leave detached HEAD state

Right now, your HEAD should still be 'detached' from Lesson 1 when you checked out an old commit. To fix that, run the command <kbd>git checkout master</kbd> You'll learn more about what this command does later this lesson.

### Making a branch

- Check all the branches we have:
<kbd> git branch </kbd>

- We create a new branch with the name <bold> exp </bold>:
<kbd> git branch exp </kbd>

- We checkout that branch:
<kbd> git checkout exp </kbd>

Whenever a create a new context or an experimental move, it is a good time to create a new branch. It is also important to have a master branch that always works. The Master branch should be the production branch.

<kbd>git checkout -b new_branch_name</kbd>=<kbd> git branch new_branch_name </kbd>+<kbd>git checkout new_branch_name</kb>

### Merging files

<kbd>git checkout master_branch</kbd>
<kbd>git merge master_branch other_branch - "merge master with coins branch"</kbd>

To know which changes were introuduced from its parent

<kbd>git show</kbd>

### Conflict detection

Sometimes we try to make a merge with two functions located in the same area of your file.Git asks us everytime if we want to keep both functions or delete one of them.