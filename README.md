<div align="center">

# asdf-chezmoi ![Build](https://github.com/psvo/asdf-chezmoi/workflows/Build/badge.svg) ![Lint](https://github.com/psvo/asdf-chezmoi/workflows/Lint/badge.svg)

[chezmoi](https://www.chezmoi.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add chezmoi
# or
asdf plugin add chezmoi https://github.com/psvo/asdf-chezmoi.git
```

chezmoi:

```shell
# Show all installable versions
asdf list-all chezmoi

# Install specific version
asdf install chezmoi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global chezmoi latest

# Now chezmoi commands are available
chezmoi --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/psvo/asdf-chezmoi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Petr Svoboda](https://github.com/psvo/)
