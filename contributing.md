# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test tfsort https://github.com/jtzero/asdf-tfsort.git "tfsort --help"
```

Tests are automatically run in GitHub Actions on push and PR.
