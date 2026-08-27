# Contributing

Conventions for working in the Data & AI team's repositories.

## Pull requests

1. Branch off the default branch.
2. **Open your PR as a draft first.** Mark it "Ready for review" only when you actually want review, so code owners are not pinged and the full CI suite does not run while you are still iterating.
3. Fill in the pull request template: what changed, why, and how you validated it.
4. Keep PRs focused and reasonably small.
5. We squash-merge, so the PR title becomes the commit message. Make it clear.

## Reviews

PRs need an approving review before merging. Code owners (see each repo's CODEOWNERS) are requested automatically.

## Repository standards

Our repositories share a few conventions:

- **CODEOWNERS** are generated from Terraform (the owning team's `maintain_repositories` in `swapfiets-terraform`), not hand-edited. Change ownership there.
- **`.gitignore`** keeps a `/temp/` section for personal scratch space (local notes, never committed).
- Each repo keeps a concise **`CLAUDE.md`** / developer guide at its root.
- Repository settings (branch protection, squash-merge, Dependabot) are managed in Terraform, not in the GitHub UI.
