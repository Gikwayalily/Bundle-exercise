Bundle1- exercise2


PS C:\Users\dotto\OneDrive\Desktop\thegym> git init
Initialized empty Git repository in C:/Users/dotto/OneDrive/Desktop/thegym/.git/
PS C:\Users\dotto\OneDrive\Desktop\thegym> git branch -M main
PS C:\Users\dotto\OneDrive\Desktop\thegym> git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html
        readme.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\dotto\OneDrive\Desktop\thegym> git add .
PS C:\Users\dotto\OneDrive\Desktop\thegym> git commit -m "addition of home page file"
[main (root-commit) fdd624f] addition of home page file
 2 files changed, 12 insertions(+)
 create mode 100644 home.html
 create mode 100644 readme.md
PS C:\Users\dotto\OneDrive\Desktop\thegym> 
 
 About-us page

        (use "git restore <file>..." to discard changes in working directory)
        modified:   about-us.html

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\dotto\OneDrive\Desktop\thegym> git add about-us.html
PS C:\Users\dotto\OneDrive\Desktop\thegym> git stash
Saved working directory and index state WIP on main: 80a1255 addition of about-us file
PS C:\Users\dotto\OneDrive\Desktop\thegym> git stash list
stash@{0}: WIP on main: 80a1255 addition of about-us file
PS C:\Users\dotto\OneDrive\Desktop\thegym>



