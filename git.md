# Git

## One Time Setup

`git config --global user.name "Tim Padjen"`
`git config --global user.email "tpadjen@gmail.com"`

## Project Setup

`git init`

## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage related changes
    * git add
3. Commit changes with a message
    * git commit -m "Message"

## Commands

* status -> tell me what files have been staged or committed
* add -> add a file to the stage
* rm --cached -> remove file from stage
* git commit -m "Present tense description of what changed"
* git log -> Enter to move down, q to quit
* git checkout -- filename  -> discard changes

## Problems
* commit without -m -> Use Esc :wq to quit Vim
* wrong message -> git commit --amend -m "New message"