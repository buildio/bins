# ⚠️ DEPRECATED - Build.io CLI Releases

## DEPRECATION NOTICE

**This repository is deprecated and will be permanently decommissioned on December 31, 2025.**

### Migration Information

The Build.io CLI releases have been moved to their proper location in the main CLI repository:
- **New releases location**: https://github.com/buildio/cli/releases
- **Latest release**: https://github.com/buildio/cli/releases/latest

### Background

This repository (`buildio/bins`) was created as a short-term workaround for hosting Build.io CLI binary releases. It has now been replaced by standard GitHub Action-based releases directly in the CLI repository itself.

### What Changed

- Releases are now automatically created by GitHub Actions when version tags are pushed to the [buildio/cli](https://github.com/buildio/cli) repository
- The build process uses Alpine Linux to create fully static binaries for maximum portability
- The [Build.io CLI CNB Buildpack](https://github.com/buildio/buildpack-bld-cli) has been updated to use the new release location

### Timeline

- **Now - December 31, 2025**: This repository will remain accessible for backward compatibility
- **January 1, 2026**: This repository will be permanently removed

### Action Required

If you have any scripts or systems that reference releases from this repository, please update them to use:
```
https://github.com/buildio/cli/releases/latest/download/bld-linux-amd64.zip
```

Instead of:
```
https://github.com/buildio/bins/releases/latest/download/bld-linux-amd64.zip
```

---

*For questions or concerns, please open an issue in the [buildio/cli](https://github.com/buildio/cli) repository.*