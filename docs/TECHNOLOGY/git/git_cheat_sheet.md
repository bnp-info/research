---
layout: default
title: My Git Cheat Sheet
parent: Git Version Control
grand_parent: TECHNOLOGY
has_children: false
---

# My Git Cheat Sheet

## Create a Branch from a Commit

Use this procedure to create a new branch from a commit (i.e. from a detatched HEAD) and to (optionally) push the new branch up to the origin (e.g. GitHub):

```
git checkout <commit_id>
git branch <new_branch_name>
git push origin <new_branch_name>
```