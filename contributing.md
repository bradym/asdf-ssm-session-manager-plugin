# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test ssm-session-manager-plugin https://github.com/bradym/asdf-ssm-session-manager-plugin.git "session-manager-plugin --version"
```

Tests are automatically run in GitHub Actions on push and PR.
