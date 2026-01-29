# Git Basic Commands: Status, Add, Reset, and Commit

This guide explains four fundamental Git commands that are essential for working with Git repositories.

---

## 1. git status
- This command shows the current state of your repository.
- It tells you:
  - Which branch you are on
  - Which files have been modified
  - Which files are staged for commit
- Example: git status

---

## 2. git add
- This command adds changes in your files to the staging area, preparing them for commit.
- You can add a single file:  
git add filename.md
- Or all files at once:
git add *

---

## 3. git reset
- This command removes changes from the staging area but keeps them in your working directory.
- Useful if you added a file by mistake:  
git reset filename.md

---

## 4. git commit
- This command saves the staged changes to the local repository.
- Each commit should have a meaningful message describing the changes:
git commit -m "Add introduction notes"
- After committing, your changes are saved locally and can later be pushed to GitHub.

---

### Personal Advice
- Always check your repository status with `git status` before adding or committing.
- Make small commits with clear messages for easier tracking.
- Use `git reset` if you staged something by mistake, so you can fix it before committing.
