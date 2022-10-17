# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test granted https://github.com/mameen-omar/asdf-granted.git "granted -v"
```

Tests are automatically run in GitHub Actions on push and PR.
