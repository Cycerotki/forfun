#forfun

Use these steps to upload a git repo to Github (credits to https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
1. In the directory of your choice, use git init
2. Add files into the directory
3. To check status of your files in repo, use git status
4. To add them to your Github repo, use git add <filename>
5. Then commit using git commit -m "my-message"
6. Create a new branch to store your commits via git checkout -b <make a branch name here>
7. See the current branch using git branch
8. Switch branches using git switch <branchname> or git checkout <branchname>
9. If your repo isn't created yet, go create one. Then follow the instructions on '....or push an existing repository from the command line'
10. To push your new branch, use git push origin <branchname>
11. On GitHub, open a pull request to merge branch with main
12. Then merge online, or you can follow instructions to merge with main branch from your terminal
13. Delete the branch online using git push origin --delete <branchname>
14. Delete your local git branch using git branch -d localBranchName

Extra steps:
1. To login to git from terminal, add your username and email using git config --global user.name and git config --global user.email
2. To remove your credentials, use:
  git config --global --unset user.name
  git config --global --unset user.email
  git config --global --unset credential.helper
3. If you need to login during git push, go and generate personal acces tokens (user icon > settings > Developer settings > Personal Access Token). Use the token id as your password for the git push password
