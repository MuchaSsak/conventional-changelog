# Automatic releases 📃

Generate semantic changelogs, bump package versions and create GitHub releases with apprioprate tags. All automated by GitHub Actions.

## More information

The action runs on every `push` on the `main` branch. It may also push the new/updated `CHANGELOG.md` file and update the `package.json` file depending on your commit message. This system is based on [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

## Repository settings

⚠️ In order for the actions to work, you need to enable **Read and write permissions** and **Allow GitHub actions to create and approve pull requests** Workflow permisions in the `Actions > General` tab. These settings are turned off by default, but it's important that you enable them. [Learn more about managing permisions here](https://docs.github.com/en/actions/security-guides/automatic-token-authentication#modifying-the-permissions-for-the-github_token).

## License

[MIT](https://choosealicense.com/licenses/mit/)
