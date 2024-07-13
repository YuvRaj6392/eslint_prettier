#For pre-commit hooks
- npm install --save-dev husky
- npx husky init
- Update .husky/pre-commit with "npm prettier" "git add ."
- git commit -m "init" --no-verify(for no precommit -check)