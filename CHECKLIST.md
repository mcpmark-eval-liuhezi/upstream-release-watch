# Release Checklist — GitHub CLI `v2.102.1`

Checklist for processing the latest GitHub CLI (`cli/cli`) release that our internal tooling is pinned to.

## Release under audit

| Field | Value |
| --- | --- |
| Repository | `cli/cli` |
| Release tag | `v2.102.1` |
| Release name | GitHub CLI 2.102.1 |
| Publish date | 2026-10-20T19:35:51Z |
| Full commit SHA | `89d7dcec017194af1d6f8853176b2dae9c1da762` |
| First line of commit message | `Bump golang.org/x/net to v0.60.0` |
| Commit author | williammartin |

## Tasks

Tracked as sub-issues of `Upstream release audit: GitHub CLI`:

- [ ] **Update pinned GitHub CLI version in tooling docs** (#2)
  - Applies to release tag `v2.102.1`
  - Locate every place the pinned `gh` version is referenced in the tooling docs and bump it to `2.102.1`.
  - Link the source release: https://github.com/cli/cli/releases/tag/v2.102.1

- [ ] **Run smoke tests against the new GitHub CLI release** (#3)
  - Applies to release tag `v2.102.1`
  - Install `gh` 2.102.1 (commit `89d7dcec017194af1d6f8853176b2dae9c1da762`) and run the internal smoke test suite.
  - Confirm no regressions in the commands and flags our scripts depend on.

## Sign-off

- [ ] Both sub-issues closed out
- [ ] Audit record in `docs/upstream-releases.md` still accurate
