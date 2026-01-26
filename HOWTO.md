# GladargUI: Update Cheat Sheet

Follow these steps whenever you want to push a new version to CurseForge.

### 1. Update the Code
- **Crucial:** Update `## Version: X.X.X` in `SharedMedia_Gladarg.toc`.

### 2. Run the Update Batch
Paste this into the VS Code terminal (replace `v1.x.x` with your new version):

```bash
git add .
git commit -m "Updated strings"
git tag v1.0.0
git push origin main
git push origin v1.0.0