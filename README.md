![](https://i.imgur.com/G07I9tF.png)

Command-line version of IdeaBlock for git-like idea push in workflows.

Table of Contents
-----------------

- [Download](#download)
- [Usage](#usage)

# Download
Prerequisites: NodeJS and npm
Install ideablock-cli globally using npm:
```bash
$ npm i -g ideablock-cli
```

# Usage
IdeaBlock CLI bundles the current version of all files in the current working directory and assumes that the directory is flat (in other words, files in subdirectories are not included in the idea upload).

Inside the directory in which an idea's files are stored, open your terminal and run:
```bash
$ npm run idea
```
