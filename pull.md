## Pull request

1. Fork original repo
2. Clone forked copy (personal repo)
3. Create a new branch in personal repo (git checkout -b new-branch-name)
4. Make changes and commit to branch
5. Push branch to personal repo (git push origin new-branch)
6. Update personal repo (main branch) to match original repo
a) git remote add upstream https://github.com/original-owner-username/original-repo-name.git
a.5) You can use git remote -v to list what remote options you have.
b) use git fetch upstream to sync personal repo with original repo (this creates a new branch called upstream/main)
c) Merge upstream/main with the local main branch (git merge upstream/main)
7. Create a new pull request using GitHub website (this will let you choose the branch of the original repo and the branch of personal repo you want to merge)
8. Add a title and comments to help the maintainers.
9. The maintainers will review the request.
