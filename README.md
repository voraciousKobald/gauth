# gauth
## WHAT IT IS
This utility automatically connects your github developer token to the local repo using an interactive prompt.
## DEPENDENCIES
-   [git](https://archlinux.org/packages/git-git "git at the AUR")
-   [github-cli](https://archlinux.org/packages/extra/x86_64/github-cli/ "github-cli at the AUR")
## HOW TO USE IT
First, make sure you have the dependencies listed above. Then, clone this repo by doing `git clone https://github.com/voraciousKobald/gauth` and navigating to the cloned repo and running `bash SETUP`

The SETUP creates the alias to gauth and it creates the folder where you store your token, that being `~/gtoken/token`

Now, before running gauth, run `gh` and follow the instructions it gives you, since it needs to sign you in.

Once you got that done, you should be able to run gauth.

Make sure you are inside the local repo you want to connect to, otherwise gauth wont work because it cant find the .git file.
