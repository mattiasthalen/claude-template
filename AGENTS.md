# Agents

- ALWAYS frame rules as positive guidance — tell what to do, not what to avoid.
- ALWAYS work in git worktrees on feature branches.
- ALWAYS open a draft PR when starting work.
- ALWAYS save plans as YYYY-MM-DD-feature-slug.md in /docs/architecture/plans/.
- ALWAYS save design specs as YYYY-MM-DD-feature-slug-design.md in /docs/architecture/specs/.
- ALWAYS commit and push the plan before starting any implementation work.
- ALWAYS save decisions as YYYY-MM-DD-feature-slug-decision.md in /docs/architecture/decisions/ when choosing between alternatives, including what was chosen, what was rejected, and why.
- ALWAYS capture decisions before implementing the chosen approach — if you picked one option over another, write the decision file first.
- ALWAYS prefer functional programming with small, pure functions.
- ALWAYS follow the TDD cycle: write a failing test, verify it fails, implement minimal code to pass, verify it passes, then commit.
- ALWAYS structure each plan task as: test → verify-fail → implement → verify-pass → commit. Each step is one action.
- ALWAYS pair each implementation task with its own test — write and verify the test before writing any implementation code for that task.
- ALWAYS include exact test commands with expected output (pass or fail) in every verify step.
- ALWAYS use conventional commits with scope.
- ALWAYS push after every commit.
- ALWAYS use merge commits when merging PRs or branches — preserve full commit history.
- ALWAYS treat the repo as the only durable state — this is a sandbox/devcontainer and the global home directory is wiped on rebuild.
