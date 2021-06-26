kg8m/textlint-editor-rules
==================================================

kg8m's textlint-editor rules for [@textlint/editor](https://github.com/textlint/editor) worker scripts.


Usage
--------------------------------------------------

1. Update rules
1. Update version in `package.json`
1. Automatically build with [kg8m/textlint-editor-rules/actions](https://github.com/kg8m/textlint-editor-rules/actions)
1. Install on https://kg8m.github.io/textlint-editor-rules/


Test rules
--------------------------------------------------

```sh
export REPO_NAME="textlint-editor-rules"
export HOMEPAGE="https://github.com/kg8m/textlint-editor-rules"
npm run website -- --metadataName="${REPO_NAME}" --metadataNamespace="${HOMEPAGE}" --metadataHomepage="${HOMEPAGE}"
npx http-serve dist/
```
