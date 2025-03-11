# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test helmify https://github.com/0hlov3/asdf-helmify.git "helmify --help"
```

Tests are automatically run in GitHub Actions on push and PR.
