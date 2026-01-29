<div align="center">

# asdf-tfsort [![Build](https://github.com/jtzero/asdf-tfsort/actions/workflows/build.yml/badge.svg)](https://github.com/jtzero/asdf-tfsort/actions/workflows/build.yml) [![Lint](https://github.com/jtzero/asdf-tfsort/actions/workflows/lint.yml/badge.svg)](https://github.com/jtzero/asdf-tfsort/actions/workflows/lint.yml)

[tfsort](https://github.com/AlexNabokikh/tfsort) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `uname`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add tfsort https://github.com/jtzero/asdf-tfsort.git
```

tfsort:

```shell
# Show all installable versions
asdf list-all tfsort

# Install specific version
asdf install tfsort latest

# Set a version globally (on your ~/.tool-versions file)
asdf set --home tfsort latest

# Now tfsort commands are available
tfsort --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtzero/asdf-tfsort/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [jtzero ?](https://github.com/jtzero/)
