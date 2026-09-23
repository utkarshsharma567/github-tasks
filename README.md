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
