# Issue #754 investigation: Improve Web IDE instructions

**Upstream issue:** https://gitlab.com/gitlab-org/developer-relations/contributor-success/team-task/-/work_items/754  
**Project:** `gitlab-org/developer-relations/contributor-success/team-task`  
**Issue status when reviewed:** Open  
**Work status in this repository:** Investigation notes only

## Problem described in the issue

The discussion around the first-contribution tutorial raised several points of confusion for new contributors:

1. The Web IDE link in the tutorial leads to explanatory documentation rather than directly opening the Web IDE, or the tutorial should clearly offer both destinations.
2. Contributors may not understand that they need to navigate from the main GitLab project to a community fork before opening the Web IDE.
3. The purpose and benefits of community forks are not explained clearly enough.
4. Contributors who do not yet have access to community forks need a workable alternative. The discussion noted a mismatch between encouraging people to start early and a flow that requires fork access.

## Why implementation was not started

The issue discussion did not establish one agreed implementation. The issue author described it as a topic to discuss and decide how to make the Web IDE easier to find and open, rather than specifying a single accepted patch.

Because the solution is ambiguous, making a documentation change without confirmation could solve the wrong problem or conflict with the intended contributor onboarding flow.

## Suggested options to discuss with maintainers

These are proposals for discussion, not accepted requirements:

- Provide two clearly labelled destinations: **Web IDE documentation** and **Open the Web IDE**.
- Add a short, numbered explanation showing how to reach the community fork and launch the Web IDE.
- Explain in plain language what a community fork is and why the contributor should use it.
- Add a separate path for contributors who do not yet have community-fork access, including where to request access or how to proceed without it.

Before implementing any option, confirm the expected onboarding flow, the correct target project/branch, and whether screenshots or direct links are preferred.

## Verification checklist before submitting an upstream change

- [ ] Re-read the latest issue description and discussion.
- [ ] Confirm with an issue maintainer which solution is wanted.
- [ ] Verify all tutorial links and access requirements against the current GitLab UI.
- [ ] Make the smallest change that matches the agreed solution.
- [ ] Run any relevant documentation checks.
- [ ] Submit a merge request to the upstream project and link issue #754.
- [ ] Update this work log only after the upstream state is verified.

## Honest status

No upstream files were changed as part of this investigation. No merge request was created for issue #754. This repository records the investigation and possible next steps; it is not evidence of an accepted or merged GitLab contribution.
