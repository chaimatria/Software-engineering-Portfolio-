Software-Engineering-Portfolio

Team Portfolio represents a collaborative Software Engineering project where we applied real-world development practices to design, implement, and evaluate a functional application prototype.

TEAM PORTFOLIO WEBSITE

This repository hosts our collaborative Team Portfolio Website, developed for the Software Engineering Programming Assignment at ENSIA.
The goal was to apply real-world engineering methods using Git and GitHub, following the feature-branch workflow, pull requests, and peer review.
Our final website is deployed via GitHub Pages.

TEAM MEMBERS

Chaima Traia – https://github.com/chaimatria

Zemmal Kounouz – https://github.com/Kounouz-Zl

Aya Khoumari – https://github.com/AYA-KHOUMARI

Abdelmalek Nedjar – GitHub:https://github.com/Abdelmalek05

DEPLOYED WEBSITE

The live version of our project is available at:
https://github.com/chaimatria/Software-engineering-Portfolio-.git

TEAM RETROSPECTIVE ANALYSIS
Technical Challenge

Our main technical challenge was managing merge conflicts in index.html. Since each member edited the same section to add their profile link, conflicts occurred often.
Initially, it was unclear how Git detected overlapping changes. We improved communication and synchronized our branches using
git pull origin develop
before committing. Some conflicts still required manual handling.

Merge Conflict Resolution

A major conflict occurred when two members edited the same part of index.html. Git marked the conflicting lines, and we manually reviewed both versions, keeping both names on separate lines.
We then ran:

git add index.html  
git commit -m "fix: resolve merge conflict in index.html"


This solved the issue and preserved all contributions. The experience strengthened our understanding of manual conflict resolution and version control discipline.

Pull Request and Peer Review

The pull request system improved our project’s organization and code quality. Each member developed on their own branch and submitted a PR to merge into develop.
Before merging, another member reviewed and approved the code. This process caught small errors, ensured consistent formatting, and taught us better collaboration practices.
By exchanging reviews, we learned new coding styles and built a cohesive, high-quality project.

This project reflects our team’s collaboration, communication, and growth. The time and effort invested were valuable lessons in teamwork and professional software development.