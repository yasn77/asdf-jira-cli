# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test jira-cli https://github.com/yasn77/asdf-jira-cli.git "jira version"
```

Tests are automatically run in GitHub Actions on push and PR.
