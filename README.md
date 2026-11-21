# quarry-cli

`quarry` turns declarative dataset manifests into reproducible build artifacts.
Every build is content addressed; every shard carries a digest in the lockfile.

## Commands

- `quarry plan` - show what a build would do
- `quarry build` - materialise the artifacts
- `quarry verify` - check artifacts against the lockfile
