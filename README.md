# protected-branch-test

- option to protect your main branch appears when you first create/push a new branch to your GitHub repo
- click "Protect this branch"
- branch name pattern auto-filled as `main` (so main will be protected)
- select rules (can check multiple rules) - more options pop up when a rule is selected (e.g. when "Require a pull request before merging" is selected, you can then choose (a) the number of approvals required before merging, (B) to dismiss stale PRs when new commits are pushed, and (c) require an approved review in PRs condining files with a designated code owner)


NOTES:
- Branch protection rules define whether collaborators can delete or force push to the branch and set requirements for any pushes to the branch, such as passing status checks or a linear commit history
- Can only enforce rules on public repositories when using GitHub Free plan 