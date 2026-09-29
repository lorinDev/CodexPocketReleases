# Codex Pocket Releases

This public repository distributes signed Codex Pocket Android APKs and the version catalog used by Build CLI. The application source remains in the private `lorinDev/CodexPocket` repository.

- Test APKs are published as GitHub pre-releases.
- `catalog.json` lists the current test and stable builds with their SHA-256 digests.
- Build CLI verifies the digest, package name, and signing certificate before opening Android's installer.
