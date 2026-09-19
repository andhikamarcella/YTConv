# Migration to YTConv 1.7.7

YTConv 1.7.7 is a maintenance release for the npm CLI. It updates release metadata and documentation to 1.7.7 and removes long-dash punctuation from the donation presentation.

## Upgrade

```bash
npm install --global ytconv@1.7.7
ytconv --version
```

The CLI remains free to use. Existing download, conversion, authentication, history, configuration, and diagnostic features remain available.

## Donation presentation

The donation heading and donation menus now use ordinary punctuation and plain separators instead of long dash characters.

## Release checks

The package metadata, lockfile, release-aware tests, iSH version, documentation URLs, and CI checks are synchronized with 1.7.7.

For the previous feature release, see [Migration to 1.7.6](MIGRATION-1.7.6.md).
