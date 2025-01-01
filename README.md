# Git & GitHub Ultimate guide for Indie Hacker
---
$ git init
Initialized empty Git repository in C:/git-aa/TimeShield/.git/

$ git config --global user.name "Abdullah Adeeb"

$ git config --global user.email "abdullah@abdullahadeeb.xyz"

$ git config --global core.editor "code --wait"

$ git config --global core.autocrlf true # true for windows. use input for macOS.

$ git commit -am "0.0.2"
[master (root-commit) daaa016] just a test
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

$ git branch -M main

$ git remote add origin https://github.com/AbdullahAdeebx/git-learning.git

$ git push -u origin

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 247 bytes | 123.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/AbdullahAdeebx/git-learning.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.