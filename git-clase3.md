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

