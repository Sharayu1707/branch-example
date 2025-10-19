# branch-example

🧩 Overview

Git branches allow you to work on different versions of a project simultaneously.
Each branch is like a separate workspace where changes can be made without affecting the main code.
This makes development, testing, and collaboration easier.

✅ Key Concepts

Main Branch (main/master): The default branch containing stable code.

Feature Branch: Used to develop new features independently.

Bugfix Branch: Used to fix issues without affecting the main branch.

Merge: Combining changes from one branch into another.

Conflict: Happens when changes in two branches clash; must be resolved manually.

🏠 Common Commands

### Check current branch
git branch

### Create a new branch
git branch <branch-name>

### Switch to a branch
git checkout <branch-name>

### Create and switch in one command
git checkout -b <branch-name>

### Merge a branch into current branch
git merge <branch-name>

### Delete a branch
git branch -d <branch-name>

✅ Advantages of Branching

Isolates features or fixes from main code.

Allows multiple developers to work in parallel.

Helps in testing without breaking the main project.

Makes version control organized and flexible.

🏁 Conclusion

Branches make Git powerful by allowing independent development, easy collaboration, and safe experimentation.
Using branches effectively keeps the project organized and reduces risks of breaking the main code.
