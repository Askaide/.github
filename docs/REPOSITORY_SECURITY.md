# Repository Security Baseline

This public repository is intentionally documentation-only.

## Recommended Organization Protections

Use repository policies or rulesets where available to reduce accidental damage:

- restrict repository visibility changes;
- restrict repository deletions;
- restrict repository transfers;
- keep public repositories reviewed and minimal;
- keep private application repositories private.

If GitHub warns that organization rulesets require GitHub Team, keep the policy documented and use owner discipline until enforcement is available.

## Recommended Repository Settings

For public repositories:

- require review before publishing sensitive material;
- avoid public issues for account-specific support;
- avoid publishing screenshots containing private data;
- keep secrets out of git history;
- keep public docs small, intentional and maintained.

For private repositories:

- keep visibility private;
- protect main branch;
- require signed or reviewed changes where practical;
- store secrets in environment-specific secret managers, not in git;
- never commit production `.env` files or signing keys.

## Public Issue Policy

GitHub issues are not a support channel for:

- account access;
- billing;
- personal data;
- marketplace disputes;
- private security details.

Use official Askaide support instead:

```text
https://askaide.com/fr/contact
```
