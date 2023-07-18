<div align="center">

# asdf-tfsec [![Build](https://github.com/woneill/asdf-tfsec/actions/workflows/build.yml/badge.svg)](https://github.com/woneill/asdf-tfsec/actions/workflows/build.yml) [![Lint](https://github.com/woneill/asdf-tfsec/actions/workflows/lint.yml/badge.svg)](https://github.com/woneill/asdf-tfsec/actions/workflows/lint.yml)

[tfsec](https://aquasecurity.github.io/tfsec) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add tfsec
# or
asdf plugin add tfsec https://github.com/woneill/asdf-tfsec.git
```

tfsec:

```shell
# Show all installable versions
asdf list-all tfsec

# Install specific version
asdf install tfsec latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tfsec latest

# Now tfsec commands are available
tfsec --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/woneill/asdf-tfsec/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bill O'Neill](https://github.com/woneill/)
