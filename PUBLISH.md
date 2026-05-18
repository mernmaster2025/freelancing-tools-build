# Publish a release

This repository ([freelancing-tools-build](https://github.com/mernmaster2025/freelancing-tools-build)) hosts Windows release files only.

## 1. Copy build output from the main app repo

After `.\build\windows\build.ps1` in **Proposal-Generator-Translator**, copy into this repo root:

- `FreelancingTools-<version>-portable.zip`
- `installer/FreelancingTools-Setup-<version>.exe`
- `README.md`, `donate-qrcode.png` (optional, for the repo; not attached by the release action)

## 2. Commit and tag

```bash
git add .
git commit -m "Release 1.0.0"
git tag v1.0.0
git push origin main
git push origin v1.0.0
```

Pushing the tag runs **Release** and uploads the portable zip and installer to GitHub Releases.
