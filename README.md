# BinToss/scoop-bucket

[![Tests](https://github.com/bintoss/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml) [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/bintoss/scoop-bucket/actions/workflows/excavator.yml)

BinToss' bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

This small bucket is intended for maintaining packages I want to use, but have not been updated in quite some time. If other Scoop users find this bucket useful, that's a bonus.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add bintoss https://github.com/bintoss/scoop-bucket
scoop install bintoss/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
