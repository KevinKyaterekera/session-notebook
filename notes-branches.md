## Branches:

When working on a project, especially as a team, you want to work on features independently, so they never affect anyone else's work. Git offers us branches to keep our current work away from a teams common codebase until completion.

A branch lets you split from the main line of development. The new branch shares a part of its commit history with the main branch. At a certain commit the new branch branches off and the commit histories differ. <br>

## Naming branches

It is good practice to use short descriptive names for your feature branches, e.g. "contact-form". We recommend using hyphens as separators as they make the name more comfortable to read.<br>

### Branch commands<br>

- git switch -c <branchname> --> create an new branch and switch to it<br>
- git switch <branchname> --> switch branches<br>
- git branch --> list your branches<br>
- git branch -a --> list all branches local and remote<br>
- git branch -d <branchname> --> delete branch
- git push -u origin <branchname> - pushing the new branch to GitHub

## Pull requests

GitHub offers us pull requests (PR) which we can use as a convenient way to request reviews of the work on a feature branch.<br>

A pull request is a request to merge one branch into another branch. Other developers review the PR and suggest changes. If a pull request is approved we can merge the feature branch into the main branch.<br>

### Basic Workflow for a pull request

1. Create a new branch with git switch -c <branchname>.
2. Make changes to the code / write your code fpr the feature.
3. Push the changes and the new branch with git push -u origin <branchname> (after you have done this once you can use git push for this branch)
4. Create a pull request on GitHub from the new branch into main
5. Share the pull request with your team
6. Review the pull request, implement changes if needed, push again to update the pull request until it gets approved
7. Merge the pull request into main
8. Don't forget to git pull inside the main branch on your local machine
9. Delete the new branch on GitHub and locally
