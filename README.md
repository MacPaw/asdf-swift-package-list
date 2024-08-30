<div align="center">

# asdf-swift-package-list [![Build](https://github.com/MacPaw/asdf-swift-package-list/actions/workflows/build.yml/badge.svg)](https://github.com/MacPaw/asdf-swift-package-list/actions/workflows/build.yml) [![Lint](https://github.com/MacPaw/asdf-swift-package-list/actions/workflows/lint.yml/badge.svg)](https://github.com/MacPaw/asdf-swift-package-list/actions/workflows/lint.yml)

[swift-package-list](https://github.com/FelixHerrmann/swift-package-list) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add swift-package-list
# or
asdf plugin add swift-package-list https://github.com/MacPaw/asdf-swift-package-list.git
```

swift-package-list:

```shell
# Show all installable versions
asdf list-all swift-package-list

# Install specific version
asdf install swift-package-list latest

# Set a version globally (on your ~/.tool-versions file)
asdf global swift-package-list latest

# Now swift-package-list commands are available
swift-package-list --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MacPaw/asdf-swift-package-list/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [MacPaw](https://github.com/MacPaw/)
