# github-tasks
# Git Merge Lab
//merge repo

This repository is for practicing:

- Git branches
- HEAD
- Commits
- Git merge
- Merge conflicts
- Git pull
- Git push

## Goal

I am intentionally creating merge conflicts
and solving them to understand Git better.


//git fetch or git pull
 ---git fetch---
git fetch — sirf changes download karo
git fetch origin

Ye GitHub se latest commits download karega, lekin tumhari current branch mein automatically merge nahi karega.

Example:

Tumhare local mein:

A---B---C   ← main

GitHub par:

A---B---C---D---E   ← origin/main

Tum:

git fetch origin

ke baad:

A---B---C       ← main
         \
          D---E ← origin/main

Tumhari main branch abhi bhi C par hai. Bas tumhe pata chal gaya ki remote par D aur E aa gaye hain.

--git pull--
git pull — fetch + merge/rebase
git pull origin main

Generally ye:

git fetch
git merge

jaisa kaam karta hai (configuration ke hisaab se pull rebase bhi kar sakta hai).

Agar remote par D aur E naye commits hain:

Before pull:

A---B---C       ← main
         \
          D---E ← origin/main

git pull ke baad:

A---B---C---D---E   ← main

Matlab remote changes download bhi hue aur tumhari current branch mein integrate bhi ho gaye.


