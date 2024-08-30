<div align="center">

# asdf-spotbugs [![Build](https://github.com/jiahuili430/asdf-spotbugs/actions/workflows/build.yml/badge.svg)](https://github.com/jiahuili430/asdf-spotbugs/actions/workflows/build.yml) [![Lint](https://github.com/jiahuili430/asdf-spotbugs/actions/workflows/lint.yml/badge.svg)](https://github.com/jiahuili430/asdf-spotbugs/actions/workflows/lint.yml)

[spotbugs](<TOOL HOMEPAGE>) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add spotbugs
# or
asdf plugin add spotbugs https://github.com/jiahuili430/asdf-spotbugs.git
```

spotbugs:

```shell
# Show all installable versions
asdf list-all spotbugs

# Install specific version
asdf install spotbugs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global spotbugs latest

# Now spotbugs commands are available
spotbugs -help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jiahuili430/asdf-spotbugs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jiahui Li](https://github.com/jiahuili430/)
