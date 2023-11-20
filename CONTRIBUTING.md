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

- At a minimum, Issues should describe a specific problem

> ### problem
>
> Typing a specific command causes the game client to crash

- Some issues are about specific changes in behaviors. These issues should include reproduction (repro) steps with expected and actual behaviors

> 1. launch the game
> 1. type this command and hit enter
>
> expected: the command completes successfully
>
> actual: the game crashes

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

(( TODO: Explain when to create a PR and what to put in the message ))
(( TODO: Explain which branch to target for a PR ))

### Reviewing Pull Requests

(( TODO: Explain how to review changes ))
(( TODO: Explain what the requirements for approving are ))
