# Replace placeholders with values from Github Action secrets

This repository is playground to achieve this:
- Given file template with placeholders
- Using `jq` + `sed` will replace the placeholders with values from Github Actions secrets
- No need of manual determination what placeholders should be replaced

Placeholder: `__MY_SECRET_VALUE__` will get replaced with secret of name `MY_SECRET_VALUE`

Inspiration: https://github.community/t/exporting-all-secrets-in-a-workflow-action/122365/7
