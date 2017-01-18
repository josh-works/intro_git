i was try ing to find some ASCII art to add to the README, but hard to format it, at least in Vim. Maybe Atom handles line breaks better...

marginally so. Here we go:
```  
  
                /\
                ||
               ====
               |  |
               |  |
               ====
               XXXX
               |\/|
               |/\|
               |\/|
               |/\|
               |\/|
               |/\|
              /____\
              |    |
              |    |
             /      \
            /        \
           /   SPACE  \
          /      X     \
         /              \
         ----------------
         |--------------|
         |              |
         |              |
         |     ____     |
         |     |   _    |
         |     |___|    |
         |     ____     |
         |     |__      |
         |     |___     |
         |     ___      |
         |     |__]     |
         |     |  \     |
         |     ___      |
         |     |__]     |
         |     |__]     |
         |              |
         |       I      |
         |       I      |
         |       I      |
         |              |
         |     |        |
         |     |___     |
         |              |
         |              |
         |              |
         |       _      |
         |      /|      |
         |       |      |
         |     __|__    |
         |              |
         |      __      |
        /|      ||      |\
       / |      ||      | \
      /  |      ||      |  \
     /   |      ||      |   \
-----    |      HH      |    -----
|   |    |      HH      |    |   |
|   |    |      HH      |    |   |
|   |    |      HH      |    |   |
|   |    |______HH______|    |   |
--------/       HH       \--------
```

Here's a few more changes. Now I'm kicking around the [Git Plus](https://atom.io/packages/git-plus) atom extension.

Just figured out that if I make changes on `master`, and have not commited anything, and they don't conflict with any branch, i can push the changes over to a branch, real easy-like:

from branch `master`:

- `git stash`

- `git co <branch_name>`

- `git stash pop`

now `master` is clean, changes are over on `my_branch`
