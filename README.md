# caesar-smoke

Smoke test: end-to-end verification of Caesar's GitHub auth chain.

## What this proves

- [x] Caesar can read from github.com as `matokle-sudo`
- [x] Caesar can write to github.com (created this repo via the REST API)
- [x] `credential.helper = manager` resolves the PAT from Windows Credential Manager
- [x] `git push origin main` works end-to-end
- [x] Commits are authored by `matokle-sudo <matttoakley@gmail.com>`

## Status

If you can see this on https://github.com/matokle-sudo/caesar-smoke, the chain is green.
