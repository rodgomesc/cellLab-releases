# CellLab downloads

Official macOS Apple Silicon downloads and the signed automatic update feed for CellLab.

- [Download a release](https://github.com/rodgomesc/cellLab-releases/releases)
- [Signed Sparkle update feed](https://rodgomesc.github.io/cellLab-releases/appcast.xml)

This repository contains release artifacts and publishing automation only. The application source repository remains private.

CellLab verifies application updates using an embedded Ed25519 public key. Automatic updates download in the background and install after a safe quit. Existing applications without the updater need one manual installation of an updater-enabled version.

Apple Developer ID signing and notarization are separate from update-archive authentication. Each release describes its signing status.
