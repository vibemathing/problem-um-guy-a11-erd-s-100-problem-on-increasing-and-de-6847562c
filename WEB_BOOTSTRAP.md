# Web Research Bootstrap

- Repository: `vibemathing/problem-um-guy-a11-erd-s-100-problem-on-increasing-and-de-6847562c`
- Repository binding: `verified`
- Repository database ID: `1359728411`
- Repository node ID: `R_kgDOUQvPGw`
- Default branch: `main`
- Visibility: `public`
- Canonical Problem: `problem:um-guy-a11-erd-s-100-problem-on-increasing-and-de-6847562c`
- ProblemContract SHA-256: `cb41b33d6d14a672777f5e6b2d0a571de3116c1c9d285ef332292ffcc2efa725`
- Problem lifecycle: `active`
- Problem admission: `canonical_admitted`
- Harness suite: `harness-source:web-research-full` `1.1.3`
- Suite manifest SHA-256: `873d54ccacba84d38d491a10fbf185495a7cfa53dc41e91a3ba680f726d54400`
- Harness snapshot SHA-256: `22d7afc7014df58b14b21b1985d96651f8be4c2ac96d189cbb8e10a0eea12686`
- Channel: `chatgpt-web-github-issue-pr-writer`

## Required read order

1. `AGENTS.md`
2. `WEB_CHANNEL_PROFILE.json`
3. `HARNESS_SNAPSHOT.json`
4. `WEB_CONTEXT_BUNDLE.md`
5. `WEB_ACTIVE_SKILLS.json`
6. `problem-library/records/canonical-problems.jsonl`
7. `research/records/failed-routes.jsonl`
8. the current route and obligation packet named by the Issue
9. exactly the owner Skill files selected by `WEB_ACTIVE_SKILLS.json`
10. `WEB_OUTPUT_CONTRACT.json`

Return a `web-bootstrap-ack.schema.json` object before mathematical work. Hashes shown here are manifest-declared values; do not claim to have recomputed them in chat.

## Fresh-state gate precedence

At the start of every turn, refresh the default branch plus live Issue/branch/PR/check state. Current repository records outrank launch-prompt SHAs, and launch-prompt SHAs outrank old chat replies. A controlled merge may legitimately advance main or the Harness snapshot; use the fresh revision as the packet base after validating the new snapshot. Never repeat an old `BLOCK_PRE_ADMISSION` unless a fresh read proves that the exact Attempt/Route/Graph/Obligation is currently absent or mismatched.

Channel audit maturity is not repository admission. `capability_status` and connector identity fields describe how completely the exact Plugin/App identity has been audited; they do not block a repository whose current identity, canonical ProblemContract, admitted route objects, and transport controls pass. The admitted namespace remains candidate-only and grants no Evidence/Result authority.

Branch protection and automated required checks are transport controls, not demands for manual approval. Reuse the one Issue identified by `(problem_id, attempt_id, route_id, obligation_id)` and label `web-research-question`; search before create, including a second fresh search immediately before creation, so retries and concurrent turns stay idempotent.

One Web response ending is a runtime boundary, not a permission failure and not mathematical completion. Before the boundary, save the best bounded checkpoint when possible. The next turn must resume by rereading current main and live GitHub state rather than replaying a stale bootstrap decision.

## AI-native writable route

After repository admission, perform the routine candidate transport end to end without project-added human handoffs:

1. Reuse the unique Issue labeled `web-research-question` for the exact Problem/Attempt/Route/Obligation tuple; create one only after two fresh searches find none.
2. Create branch `web/attempt-<attempt-suffix>`.
3. Add, revise, or delete files only under `research/artifacts/web-inbox/**`, `research/artifacts/candidates/**`, or `research/artifacts/source-notes/**`.
4. Commit real changes and open a PR using the web candidate template.
5. Monitor required checks and, when needed, rerun the existing candidate workflow.
6. Review and revise the candidate PR; this AI review is not independent mathematical review.
7. After transport checks pass, merge the candidate PR and write the next checkpoint.

Do not create repositories, direct-push the default branch, modify workflow/truth paths, force-push, cancel/dispatch Actions, or sign Evidence/Result. Follow only platform-mandatory confirmation UI; no extra human approval is required for routine candidate operations. Issue, PR, review, merge, Actions status, command exit 0, or model self-review never closes a mathematical obligation.
