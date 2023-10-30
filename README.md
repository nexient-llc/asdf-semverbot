<div align="center">

# asdf-semverbot [![Build](https://github.com/chris-taylor-ntt/asdf-semverbot/actions/workflows/build.yml/badge.svg)](https://github.com/chris-taylor-ntt/asdf-semverbot/actions/workflows/build.yml) [![Lint](https://github.com/chris-taylor-ntt/asdf-semverbot/actions/workflows/lint.yml/badge.svg)](https://github.com/chris-taylor-ntt/asdf-semverbot/actions/workflows/lint.yml)

[semverbot](https://github.com/restechnica/semverbot/blob/main/README.md) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `curl`: to download the latest semverbot release
- `git`: for use with semverbot

# Install

Plugin:

```shell
asdf plugin add semverbot https://github.com/chris-taylor-ntt/asdf-semverbot.git
```

semverbot:

```shell
# Show all installable versions
asdf list-all semverbot

# Install specific version
asdf install semverbot latest

# Set a version globally (on your ~/.tool-versions file)
asdf global semverbot latest

# Now semverbot commands are available
sbot --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chris-taylor-ntt/asdf-semverbot/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Taylor](https://github.com/chris-taylor-ntt/)
