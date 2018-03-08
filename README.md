# gitpractice


- `git reset --hard HASH` back a single commit
  - You can either use `git log` or just specify `HEAD~1` as the commit to reset to
- Then `git reset --soft` back one more commit
- `git status` and verify that `should-be-here.md` still is
