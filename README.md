<div align="center">

# asdf-poetry [![Build](https://github.com/Azulinho/asdf-poetry/actions/workflows/build.yml/badge.svg)](https://github.com/Azulinho/asdf-poetry/actions/workflows/build.yml) [![Lint](https://github.com/Azulinho/asdf-poetry/actions/workflows/lint.yml/badge.svg)](https://github.com/Azulinho/asdf-poetry/actions/workflows/lint.yml)

[poetry](https://github.com/python-poetry/poetry) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `python`: This needs python

# Install

Plugin:

```shell
asdf plugin add poetry
# or
asdf plugin add poetry https://github.com/Azulinho/asdf-poetry.git
```

poetry:

```shell
# Show all installable versions
asdf list-all poetry

# Install specific version
asdf install poetry latest

# Set a version globally (on your ~/.tool-versions file)
asdf global poetry latest

# Now poetry commands are available
poetry --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Azulinho/asdf-poetry/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Azul](https://github.com/Azulinho/)
