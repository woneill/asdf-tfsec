# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# Example using local directory
asdf plugin test tfsec . "tfsec --version"
```

Tests are automatically run in GitHub Actions on push and PR.
