# Ben Lechlitner Resume

[![Common Changelog](https://common-changelog.org/badge.svg)](https://common-changelog.org)

A template for latex resumes using the moderncv style

## Getting Started

The `LaTeX Workshop` extension is recommended for building locally. It will compile the current tex file upon save.

Any tags in the format `v*` will kick off a release. The release action assumes that you are making use of a [changelog](/CHANGELOG.md).
Either [Common Changelog](https://common-changelog.org) or [KeepAChangelog](https://keepachangelog.com/) formats are supported.

## Editing & Tracking Changes

I use the following workflow when updating my resume and/or cover letter:

1. Create a branch (usually named after the company I'm focusing on)
1. Make changes and ensure that it builds before pushing
1. Merge branch to main (I don't do a rebase so that I have a clear delineation of changes).
1. Update changelog in main and push
1. tag changelog push with version (e.g. `v1.2.0)
   - I use `major` for format revamps, `minor` for company/job changes, `patch` for typos and grammatical fixes
