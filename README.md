## Developers

- Matthew Schulz <mkschulz@ucdavis.edu>,
- Conar Abramson-Davis <cabramsondavis@ucdavis.edu>
- Sage Zimmerman <sazimmerman@ucdavis.edu>
- Bradly Booth <btbooth@ucdavis.edu>
- Jared Pugh <jpugh@ucdavis.edu>
- Sarah Wu <ssjuw@ucdavis.edu>

## Workflow

### Before Getting Started

- Discuss what you'll be working on
- Make sure there is a GitHub issue in the repo that is tracking the item you're working on

### Get Started on a Work Item

- On GitHub
    - Assign yourself to the issue you'll work on (if not already)

- In your local Git repo
    - Switch to `main` branch (unless otherwise specified)
    - Sync latest changes on `main` branch (IMPORTANT!!!)
    - Create and checkout a new branch from `main`
        - Branch name may start with the issue ID followed by feature, like `10-code-review-doc`
    - Start coding

### Work on an Item

- Commit and push changes frequently
    - Please follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages
    - Check out the reason behind [Adopting Conventional Commits](/blog/memo-2021-07-21#adopting-conventional-commits)

- Create a pull request on GitHub as early as you make the first commit
    - Title should start with `Draft:` and followed by the feature, like `Draft: Code Review Doc`
    - Description should start with a line like `Closes #10` to let GitHub link the issue with the pull request automatically

- Write unit tests while developing new features (if applicable)

- Try to resolve merge conflicts (if any) with the target branch as you notice

### Finish up

- Clean up code
- Run and pass all related unit tests (if applicable)
- Remove `Draft:` from title of the pull request
- Request a code review
- Wait for review
- Implement feedbacks (if any) by continue adding commits and request another review
- Wait for approval and merge
