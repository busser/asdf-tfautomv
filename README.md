<div align="center">

# asdf-tfautomv [![Build](https://github.com/busser/asdf-tfautomv/actions/workflows/build.yml/badge.svg)](https://github.com/busser/asdf-tfautomv/actions/workflows/build.yml) [![Lint](https://github.com/busser/asdf-tfautomv/actions/workflows/lint.yml/badge.svg)](https://github.com/busser/asdf-tfautomv/actions/workflows/lint.yml)

[tfautomv](https://github.com/busser/tfautomv) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add tfautomv
# or
asdf plugin add tfautomv https://github.com/busser/asdf-tfautomv.git
```

tfautomv:

```shell
# Show all installable versions
asdf list-all tfautomv

# Install specific version
asdf install tfautomv latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tfautomv latest

# Now tfautomv commands are available
tfautomv --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/busser/asdf-tfautomv/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Arthur Busser](https://github.com/busser/)
