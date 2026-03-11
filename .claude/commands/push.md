Stage all changes, commit with message "update", configure git user, and push using the SSH key.

Run the following commands sequentially:
1. `git add .`
2. `git commit -m "update"`
3. `git config user.email "ycchen0506@outlook.com"`
4. `git config user.name "cyc"`
5. `GIT_SSH_COMMAND="ssh -i ~/.ssh/id_ed25519" git push`

If there are no changes to commit, skip the commit and just push any unpushed commits. If there's nothing to push either, inform the user.
