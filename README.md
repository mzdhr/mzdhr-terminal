# Mzdhr Terminal Read Me File
This repository contained my files that I used to make the Terminal better on Mac! Feel free to use any of them.

## Auto Complete Script for Git
**File Name:** git-completion.bash

**Description:** A bash completion script for git.

**How To Use:** Move it in your home directory folder. Then Add the following line to your .bash_profile:

```
source ~/git-completion.bash
```


## Git Repository Script

**File Name:** git-prompt.sh

**Description:** Script that provides useful information (in your prompt) about the repository that you are in.

**How To Use:** Move it in your home directory folder. Then add the following line to your .bash_profile:

```
source ~/git-prompt.sh
```


## My Own Bash Profile

**File Name:** bash_profile.txt

**Description:** My won custom .bash_profile for my terminal

**How To Use:** Move it to your home directory folder, Then rename it to .bash_profile *don't forget to delete the .txt*. It will be hidden therefore use nano editor from the terminal if you want to make any change to it.


## Git Template File

**File Name:** git-commit-template-and-style.txt

**Description:** Template for commit messages, help you to remember the guide rulls.

**How To Use:** Move it in your home directory folder. Then rename it, with terminal by this code:

```
mv git-commit-template-and-style.txt .gitcommitstyle.txt
```

After that run this command, to tell git that there is a global commit message template available to use.

```
git config --global commit.template ~/.gitcommitstyle.txt
```

**Note:** This file is too long if you like modify it, before rename it.
