# AIScript New Version Releases

Repository nay dung de host `latest.json` va cac goi update cho AIScript.

## Files

- `latest.json`: manifest cho app check version moi
- `releases/*.zip`: goi update de app download va apply

## Current Package Strategy

Ban dau em publish `patch zip` chi chua `resources/app.asar`.
Ly do: goi full `win-unpacked` hien tai lon hon gioi han 100 MB cua GitHub repository.

Neu can publish full package lon hon, nen dung:

- GitHub Releases assets
- Git LFS
- mot storage static khac nhu S3, R2, Backblaze
