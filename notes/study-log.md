# Study Log

## Date: 25-6-2026
## Topic: Phase 0 setup + 1st linux lab
## What I learned:
- How to create folders and files in Linux
- How to move/copy/delete files
- How to initialize a Git repo
- How to push to GitHub
- How to create and run a simple bash script
## Commands I used:
 mkdir, cd, pwd, ls, touch, cp, mv, rm, git init, git add, git commit, git push, chmod
## Problems / Errors:
 - curl was not installed
- GitHub rejected normal password authentication during `git push`
- Error message:
  `remote: Invalid username or token. Password authentication is not supported for Git operations.`
## How I fixed them: 
- Installed curl using apt
- Created a GitHub Personal Access Token (PAT)
- Used GitHub username + PAT instead of the normal password when running `git push`
## Next step: 
- Continue Linux commands
- Start Git practice repo
- Verify GitHub push works successfully with the PAT
