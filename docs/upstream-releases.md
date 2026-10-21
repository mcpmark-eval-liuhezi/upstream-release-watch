# Upstream Release Audit — GitHub CLI (cli/cli)

Permanent audit record for the GitHub CLI (`cli/cli`) releases that our internal tooling is pinned to.

## Latest audited release

| Field | Value |
| --- | --- |
| Repository | `cli/cli` |
| Release tag | `v2.102.1` |
| Release name | GitHub CLI 2.102.1 |
| Publish date | 2026-10-20T19:35:51Z |
| Full commit SHA | `89d7dcec017194af1d6f8853176b2dae9c1da762` |
| First line of commit message | `Bump golang.org/x/net to v0.60.0` |

## Commit details

- **SHA:** `89d7dcec017194af1d6f8853176b2dae9c1da762`
- **Author:** williammartin (William Martin <williammartin@github.com>)
- **Committer:** BagToad
- **First line of commit message:** `Bump golang.org/x/net to v0.60.0`

Full commit message:

```
Bump golang.org/x/net to v0.60.0

Fixes GO-2026-6603, GO-2026-6610, GO-2026-6611, GO-2026-6612 and
GO-2026-6617 reported by govulncheck.
```

## Follow-up work

Tracked in the parent issue `Upstream release audit: GitHub CLI`:

1. Update pinned GitHub CLI version in tooling docs.
2. Run smoke tests against the new GitHub CLI release.

A concrete checklist for this release lives in `CHECKLIST.md` (see the `audit/release-checklist` pull request).

## Reference

- Release: https://github.com/cli/cli/releases/tag/v2.102.1
- Commit: https://github.com/cli/cli/commit/89d7dcec017194af1d6f8853176b2dae9c1da762
