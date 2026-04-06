## Summary
- add calculator unit tests
- add GitHub Actions CI workflow
- verify CI runs automatically on pull requests

## What changed
- added tests for add(), subtract(), multiply(), divide()
- added edge case test for divide by zero
- added `.github/workflows/ci.yml`

## How to verify
- run `npm test` locally
- create a PR into `develop`
- confirm GitHub Actions checks pass

## Checklist
- [ ] branch created from `develop`
- [ ] commit messages follow convention
- [ ] tests pass locally
- [ ] CI passes on PR
