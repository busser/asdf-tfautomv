# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test tfautomv https://github.com/busser/asdf-tfautomv.git "tfautomv --version"
```

Tests are automatically run in GitHub Actions on push and PR.
