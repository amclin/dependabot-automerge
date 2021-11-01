[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

# dependabot-automerge
GitHub action to automatically merge pull requests created by Dependabot

## INACTIVE

This repo was created with the intention of building a simplified action for managing all the nuances of dependabot-based merges. However, GitHub composit actions are limited in that they cannot call other complex actions, preventing the ability to chain complex actions built out of other actions in the marketplace. There are a lot of features possible as a workflow, but not as an action. A **workflow** can aggregate multiple actions, but an **action cannot do the same**. GitHub's documentation around this is woefully incomplete, implying that anything a workflow can do, an action can also do. There's very little distinction in the docs to clarify when something is a **workflow** feature vs. an **action** feature.

Since I have no intention of recreating all the internals of other actions to do this, this project is at a standstill and will be archived. I may resurrect in the future if GitHub provides the full workflows fuctionality at the action level, but I'm not holding my breath.

Instead, please try [https://github.com/marketplace/actions/merge-me](Merge Me!) or [https://github.com/marketplace/actions/dependabot-auto-merge](Dependabot Automerge). I've been playing with both, and **Merge Me** is easier to configure and more reliable.
