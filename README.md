# run-node-with-github-actions

A template repository for running node scripts using GitHub Actions.

By default it will:

- Use the latest LTS version of node
- Run `npm start` daily at 00:00

## Using Secrets

If your node script needs to use secrets (API tokens, etc.) you can define them on
Settings › Secrets › Actions. You can read more at [GitHub's documentation about managing secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets).
