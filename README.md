# Create repo and test some commands

```bash
git config --global init.defaultBranch main
git init
gh repo create ws-try-git --public --source=. --remote=origin
git add *
git commit -am "First added to main"
git push --set-upstream origin main
```