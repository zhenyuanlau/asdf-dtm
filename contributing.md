# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test dtm https://github.com/zhenyuanlau/asdf-dtm.git "dtm --help"
```

Tests are automatically run in GitHub Actions on push and PR.
