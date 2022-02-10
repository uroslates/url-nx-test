## Commit stylegueide

We are following [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) spec for commiting the code.

In order to conform to it please make sure each of your commits is done by executing `npm run commit` script.
This would guide you through the conventional commit wizzard enforsing connectional commits format.

### Contribution Flow

This repository is using [Gihtub Flow](https://docs.github.com/en/get-started/quickstart/github-flow).
This means anything within the **main** branch is a production-ready code (always deployable).

For any new _feature/bugfix/... or any general code change_ you would like to introduce to the **main** branch, make sure you've:

1. [ ] Introduced your code changes within your branch (branched of of a _main_ branch).
2. [ ] Once ready for merging make sure your branch is **up to date with main** branch.
3. [ ] Make sure you've opened a **Pull Request** for your branch (against the main branch).
4. [ ] Make sure your commits are squashed into one meaningful commit following [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) standards. Here you can use `npm run commit` for enforcing the commit message standard on your branch (and than squashing previous commits into the last one). (make sure PR title is following conventional-commit standard with #PR_NUMBER at the end like for eg "feature: add CI/CD setup (#1)")
