# Create repo and test some commands

```bash
git config --global init.defaultBranch main
git init
gh repo create ws-try-git --public --source=. --remote=origin
git add *
git commit -am "Adding project 25012501-cathy-bourgeois Website POC 1"
git push --set-upstream upstream master
```