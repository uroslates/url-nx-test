# Github Repository Setup

Make sure you [create a github repository](https://github.com/new) for your project.

In order to make your [Project's Github repository](https://github.com/uroslates/url-nx-test) setup correctly for performing your **CI/CD actions** make sure you have done the following:

1. [ ] Set your main branch **main** -> `Branch protection rule` for your Github Repository to have **Require a pull request before merging** option selected! You can do it [here](https://github.com/uroslates/url-nx-test/settings/branch_protection_rules/new)
   1. **Branch name pattern**: _main_.
   2. Select **Require a pull request before merging** option as well as **Require approvals** option
2. [ ] Only **Allow squash merging** for pull requests - go to [Repository Settings Page](https://github.com/uroslates/url-nx-test/settings#merge-button-settings) and select **Allow squash merging** option only!
3. [ ] Create new **NPM token** - go to [https://www.npmjs.com/settings/:your_npm_username/tokens/create](https://www.npmjs.com/settings/:your_npm_username/tokens/create) or execute `npm token create` command.
4. [ ] Add generated **NPM token** as `NPM_TOKEN` secret to your Github repo [here](https://github.com/uroslates/url-nx-test/settings/secrets/actions/new).
5. [ ] (CI relevant, due to Branch Protection rules) Make sure you have a Github PAT (or create one [here](https://github.com/settings/tokens/new?scopes=repo)) with _Selected Scopes_ set to _repo_.
6. [ ] Store your Github PTA (from above step) as **GH_TOKEN** to your repo [Secrets/Actions page](https://github.com/uroslates/url-nx-test/settings/secrets/actions/new)
