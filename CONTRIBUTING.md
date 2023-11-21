# Contributing

This file is a global default for contribution instructions across all ComCODE repos. Edit it at https://github.com/comcode-org/.github/

https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file

This document outlines the standards, best practices, and guidelines we adhere to when contributing to this project. Whether you're a newcomer or a veteran contributor, please review this guide thoroughly before making any submissions. Adhering to these guidelines ensures smooth collaboration, consistent code quality, and efficient review processes. Your understanding and effort in this regard are deeply appreciated.

## Submitting changes

All changes are proposed to address an Issue and are created as Pull Requests (PR) on a topic branch. Process overview:

1. [Create an issue](#creating-issues)
1. [Create a topic branch](#creating-branches)
1. [Develop the fix on the branch](#developing-fixes)
1. [Create a Pull Request off of the branch](#creating-pull-requests-prs)
1. [Review Pull Request](#reviewing-pull-requests)
1. Merge Pull Request

### Values

- We make changes incrementally
- Our changes address clearly defined problems which are recorded in Issues
- We make Issues which describe the smallest problem they appropriately can
- We work together to ensure the quality of our Issues
- We make Pull Requests to make changes which address Issues
- Our Pull Requests are focused and make the smallest change possible to fix Issues

More details on our values and other agreements in the [working agreements document](https://github.com/comcode-org/people_and_process/blob/main/conduct/working_agreements.md).

### Creating Issues

Issues are artifacts which are used to clarify and document specific problems. Issues are created before changes to allow us to focus our changes, discuss the priority and scope of the problem being described.

- We use issue templates.
- Issues should be created on the appropriate repo where the issue can be actioned on.
- At a minimum, Issues should describe a specific problem
- Some issues are about specific changes in behaviors. These issues should include reproduction (repro) steps with expected and actual behaviors
- Sometimes Issues are used as chores or tasks which do not have corresponding changes or PRs in GitHub. These types of Issues are generally part of a larger problem or project that is being solved.
- For some simple cases where the problem being solved is very clear, no issues are required to create pull requests (e.g. typo-fixes in documentation). These PRs should include enough documentation to describe the problem.
- Our Issue creation process and policy is new. Please help us by asking questions / giving feedback in discord or github.

### Creating branches

- Topic Branches are short-lived branches where patch development happens
- Topic Branches are deleted after merge
- Topic Branches are labelled with the creators' name, but they are communal development spaces where anyone is encouraged to contribute
- Topic Branches are created off of the development branch `dev`
- Topic Branches follow the naming convention `username` `separator` `topic`, e.g. `janedev-kooltextfix`, `janedev-patch-1`, `janedev/wild-star`
- `username` can be any identifiable moniker. GitHub username is preferred
- `separator`s can be any of `/` (slash) `-` (dash) or `_` (underscore)
- `topic` should be short. It does not need to accurately describe the contents, but should not be misleading
- All branch names should be all lowercase and not use special characters outside of the separators above

### Developing fixes

(( TODO: Explain how large a commit should be (how many changes) ))
(( TODO: Explain what commit messages should be like ))

### Creating Pull Requests (PRs)

- A pull request is opened once a fix for an issue has been developed on a topic branch
- PRs should target the default branch for merge
- PR titles should be a summary of what was implemented in the PR
- The description of the PR should contain a reference to an issue which it closes using the [github notation](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) e.g. `fixes #XX`, `fixes #XX, fixes #YY`
- Context information for how the fix works and why things were breaking in the way that they were should be included in the PR description instead of commit messages
- If the changes require updates to any documentation, diagrams or other content which needs to stay in sync or be added, this should be included in the PR as well
- Applicable test cases or automation updates should be included in the PR
- If any process or policy was not followed, notes should be provided to reviewers in the PR description explaining why

### Reviewing Pull Requests

Our Pull Request review process values [optimistic merging](https://github.com/openpracticelibrary/openpracticelibrary/issues/208) from [Pieter Hintjens](http://hintjens.com/blog:106). While we don't adhere strictly to the [c4 process spec](https://rfc.zeromq.org/spec/42/#23-patch-requirements), the spirit of focusing on one problem at a time and making 'good enough' / 'correct' incremental progress is critical to our process.

As reviewers, PRs should be approved and merged if they are `Correct` as defined by following criteria:

1. All automated and manual validation tests pass on the topic branch on at least the primary platform
1. The product builds successfully on at least the primary platform
1. All applicable style and contribution guides are met
1. The PR is a focused and accurate answer to one agreed on Issue

In general, reviewers are acting in the role of maintainers in the open-source model and have the following responsibilities:

1. Are respectful stewards of Correctness
    1. Do not enforce rules outside of documentation
    1. Teach Correctness rules by referencing documentation and stating how it applies (e.g. PR focus: these lines do not apply to fixing the Issue)
    1. Update documentation and propose improvements based on reviewing experience
    1. Update automation when it doesn't match documentation
    1. Create automation to improve review process
1. Use good judgement
    1. Reduce their bias by seeking additional opinion
    1. Don't enforce process to be pedantic, be flexible
1. Are responsible for getting PRs merged
    1. Make changes to fix correctness directly in branches
    1. Follow up regularly on blockers to merging or open conversations
    1. Create and encourage creation of issues to address new problems / fixes
1. Share non-blocking improvement feedback
    1. Things like typos, spelling errors, capitalization, rephrasing (Depending on repo-specific styles some of these might be required)
    1. Ask questions for reviewer's own understanding & learning
