# Contributing to SWIR Projects

Thanks for taking the time to contribute.

## Before you start

Please check existing issues and pull requests before opening a new one. This helps avoid duplicate work.

For larger changes, open an issue first and describe:

- the problem you want to solve,
- the proposed approach,
- possible compatibility impact,
- screenshots or examples when UI behavior is involved.

## Development guidelines

- Keep changes focused and easy to review.
- Preserve existing behavior unless the change intentionally replaces it.
- Avoid unrelated formatting or refactoring in the same pull request.
- Add or update tests when practical.
- Update documentation when behavior, setup or commands change.
- Never commit credentials, tokens, private keys or personal data.
- Prefer clear names and small, maintainable functions.
- Keep platform-specific behavior explicit.

## Pull requests

A good pull request should include:

1. A clear title.
2. A short explanation of the problem.
3. A summary of the solution.
4. Testing performed.
5. Screenshots for visible UI changes.
6. Notes about breaking changes or known limitations.

## Bug reports

Please include enough information to reproduce the problem:

- application/project version,
- operating system,
- steps to reproduce,
- expected behavior,
- actual behavior,
- relevant logs or screenshots.

## Commit style

Short, descriptive commit messages are preferred. Examples:

- `fix: prevent duplicate messages`
- `feat: add theme selector`
- `docs: improve installation guide`
- `refactor: simplify export pipeline`

## Maintenance reviews

Repository refreshes include functional maintenance: source/dependencies, upstream data freshness, actual update behavior, runtime checks and release integrity. Follow [REPOSITORY_REVIEW_CHECKLIST.md](REPOSITORY_REVIEW_CHECKLIST.md), record evidence and unresolved items, and prioritize stale or broken protection data. README/image work alone is not a completed maintenance review.

## Quality bar

### Screenshots

Capture real application windows with pointer inclusion disabled. Move the pointer outside the captured window, remove keyboard focus from text inputs, and disable click highlights or capture-tool overlays before capture. Review the saved file at native resolution: no mouse arrow, I-beam, caret, pointer halo or click ring should remain. Check copied previews in portfolio pages as well as the project's own images. Preserve genuine interface text, warnings and state; recapture when an overlay obscures content that cannot be restored faithfully.

### Releases

Tie release assets to the exact tested commit and version tag. Include SHA-256 checksums, installation instructions, known limitations and the scope of runtime testing. Download uploaded files and verify them before publication. Clearly label source-only archives; they are not installers or evidence of a working packaged application.

A contribution should leave the project at least as stable and understandable as it was before the change.

Thank you for helping improve the SWIR ecosystem.


