# testing Git index issue

2022-11-17: specifically, trying to resolve this error message:

  "fatal: git/index: unable to map index file: Invalid argument"

that Mathew is getting on his Win10 system using Obsidian-git.

- on this repo I will try to test this info for rebuilding the index:

  To rebuild the index, you can simply do `git reset --mixed`. This
  makes the index look like the last commit while leaving the worktree
  alone. If you had any local changes you git added but did not commit
  yet, you will need to re-add those.
  
  from this site:
  <https://git.seveas.net/repairing-and-recovering-broken-git-repositories.html#:~:text=To%20rebuild%20the%20index%2C%20you,need%20to%20re%2Dadd%20those>
  
