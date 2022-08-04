<div align="center">

# asdf-dtm [![Build](https://github.com/zhenyuanlau/asdf-dtm/actions/workflows/build.yml/badge.svg)](https://github.com/zhenyuanlau/asdf-dtm/actions/workflows/build.yml) [![Lint](https://github.com/zhenyuanlau/asdf-dtm/actions/workflows/lint.yml/badge.svg)](https://github.com/zhenyuanlau/asdf-dtm/actions/workflows/lint.yml)


[dtm](asdf-dtm) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`

# Install

Plugin:

```shell
asdf plugin add dtm
# or
asdf plugin add dtm https://github.com/zhenyuanlau/asdf-dtm.git
```

dtm:

```shell
# Show all installable versions
asdf list-all dtm

# Install specific version
asdf install dtm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global dtm latest

# Now dtm commands are available
dtm --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zhenyuanlau/asdf-dtm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zhenyuan Lau](https://github.com/zhenyuanlau/)
