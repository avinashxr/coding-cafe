# Lab 4 Notes

## Question 1
--global applies the configuration setting to your entire user account on this machine. If left out, Git would throw an error when trying to commit because it wouldn't know your name or email for this specific repository.

## Question 2
The hidden directory `.git` appeared in `ls -a`. It contains all the version history, configuration files, and metadata that Git uses to track the repository.

## Question 3
Git is offering to track our untracked files (like README.md and week directories). Notice that the thousands of files inside `.venv/` are also hidden/ignored now (or if not yet ignored, they are listed unless ignored).

## Question 4
After creating .gitignore, everything inside `.venv/` disappeared from the untracked files list in git status.

## Question 5
.gitignore itself should be committed to the repository because your collaborators (and TAs) need it on their machines so they don't accidentally download or track junk files either.

## Question 6
README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved from the working directory into the staging area.

## Question 7
Git printed a summary showing the commit hash, the commit message, and how many files changed with insertions/deletions.

## Question 8
They are called the commit hash (or short hash). They serve as a unique ID to reference that specific commit in history.

## Question 9
The 4 steps of the Git loop are: edit files -> git status -> git add -> git commit.

## Question 10
README.md gets a special name because GitHub and other platforms automatically render it as the front page of your repository.

## Question 11
`gh auth login` securely saves an authentication token/credential on your machine, so Git can talk to GitHub using HTTPS without needing your password every time.

## Question 12
The rendered contents of README.md appear on GitHub's front page because hosting platforms automatically look for and display README files as the welcome page.

## Question 13
No, pushing does not change your local history; it only uploads a copy of your existing local commits to the remote server on GitHub.

## Question 14
A private repository exists on GitHub with its access restricted so only you and invited collaborators can view it, whereas a repository that doesn't exist on GitHub has no cloud presence or remote backup at all.


