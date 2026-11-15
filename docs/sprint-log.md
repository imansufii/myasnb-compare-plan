# Sprint 1 Log

- **Planning date:** 16 November 2026
- **Status:** Documentation tasks completed; project board pending
- **Sprint goal:** Organise the MyASNB Compare and Plan concept into a clear portfolio repository and practise the issue, branch, and pull-request workflow using genuine documentation tasks.

## Sprint backlog

| Issue | Task | Done when | Current status |
|---|---|---|---|
| [#1](https://github.com/imansufii/myasnb-compare-plan/issues/1) | Add problem statement, requirements, and user stories | The three core documents meet the CSC649 structure and testability requirements | Completed; [PR #4](https://github.com/imansufii/myasnb-compare-plan/pull/4) merged and issue closed |
| [#2](https://github.com/imansufii/myasnb-compare-plan/issues/2) | Add DSS technology brief, ideation notes, and references | The concept, three methods, diagrams, worked example, limitations, and sources are documented | Completed; [PR #5](https://github.com/imansufii/myasnb-compare-plan/pull/5) merged and issue closed |
| [#3](https://github.com/imansufii/myasnb-compare-plan/issues/3) | Add repository README, source placeholder, and Sprint 1 log | The repository is easy to review and the log records actual activity | Completed; [PR #6](https://github.com/imansufii/myasnb-compare-plan/pull/6) merged and issue closed |

## Activity log

### 16 November 2026

- Reviewed the original assignment brief and rubric, Week 2 GitHub lab, Week 3 Codespaces lab, and the current MyASNB report draft.
- Confirmed that both GitHub repositories were public and empty before this work began.
- Prepared the repository structure and documentation drafts.
- Checked the listed official ASNB, government, standards, and NIST source pages.
- The connected GitHub integration returned `403 Resource not accessible by integration` when issue creation was attempted.
- Used the authenticated Git workflow available in the environment to create the initial commit and three genuine Sprint 1 issues.
- Pushed three feature branches and opened pull requests #4, #5, and #6 for review.
- Reviewed the three pull-request diffs, confirmed that they were cleanly mergeable, and merged them using merge commits.
- Confirmed that GitHub closed issues #1, #2, and #3 through the pull-request closing references.

## Current progress

- **Completed on GitHub:** README, `.gitignore`, seven documentation files, source placeholder, three issues, three feature branches, and three merged pull requests.
- **Pending on GitHub:** create the Sprint 1 project board and add the three closed issues as evidence of the lab workflow.
- **Not started:** an application prototype, user testing, or measured performance tests.

## Blockers

- The connected GitHub integration can read the repositories but did not have permission to create issues on 16 November 2026. An authenticated GitHub API fallback was used successfully.
- The available GitHub credential does not include the `read:project` or `project` scope required for GitHub Projects, so the Sprint 1 board could not be created through the API.

## Sprint review

The documentation was checked against the repository-related rubric before merging. Pull requests #4, #5, and #6 were merged into `main`, and their linked issues were closed. The repository now contains the planned documentation structure. The Sprint 1 project board remains outstanding because the available credential lacks GitHub Projects permission.

## Retrospective

- **What went well:** The assignment rubric and report provided a clear source of truth, and separating the documentation into three issues made each pull request focused and reviewable.
- **What was difficult:** The connected integration rejected issue creation, and the available credential does not have GitHub Projects permission.
- **What I will change next:** Check repository and Projects permissions before sprint planning and update the sprint log immediately after each issue or pull-request state changes.

## Evidence checklist

- [x] Three GitHub issues created
- [ ] Issues added to a Sprint 1 project board
- [x] Feature branches pushed
- [x] Three pull requests opened
- [x] Pull requests reviewed
- [x] Completed pull requests merged
- [x] Corresponding issues closed
- [x] Sprint log updated with final links and retrospective

Do not mark an item complete until the corresponding GitHub evidence exists.
