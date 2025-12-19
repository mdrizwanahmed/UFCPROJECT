# UFC Fan Portal – Git Bash & GitHub Project

## Project Overview
This project is a hands-on implementation of Git and GitHub concepts as part of the Version Control Systems course. The project focuses on understanding how version control is used in real-world software development by managing a web-based UFC Fan Portal using Git Bash and GitHub.

The main objective of this project is not web development complexity, but effective usage of Git commands, branching strategies, merge operations, and conflict resolution.

---

## Objectives
- To understand the Git workflow including working directory, staging area, and repository
- To perform multiple commits with meaningful commit messages
- To create and manage multiple branches
- To merge branches into the main branch
- To intentionally create and resolve a merge conflict
- To use GitHub for remote repository management
- To document the entire process professionally using Markdown

---

## Project Description
The UFC Fan Portal is a single-page web application developed using HTML, CSS, and JavaScript in a single file. The project simulates a real development environment where multiple features, fixes, and experiments are carried out in parallel using different Git branches.

The development process involved continuous updates across different branches such as feature development, testing updates, bug fixes, and experimental changes. All changes were tracked and managed using Git.

---

## Branches Used
The following branches were created and used in this project:

- `main` – Stable production-ready code
- `feature` – Used to add new content and features
- `test` – Used for testing layout and content changes
- `bugfix` – Used to fix UI and formatting issues
- `experiment` – Used for experimental changes

---

## Git Commands Used
Some of the important Git commands used during this project are:

```bash
git init
git status
git add .
git commit -m "commit message"
git branch
git checkout branch_name
git merge branch_name
git remote add origin <repository_url>
git push origin branch_name

