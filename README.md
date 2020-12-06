<div align="center">

# asdf-babashka ![Build](https://github.com/fredZen/asdf-babashka/workflows/Build/badge.svg) ![Lint](https://github.com/fredZen/asdf-babashka/workflows/Lint/badge.svg)

[babashka](https://github.com/borkdude/babashka) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add babashka https://github.com/fredZen/asdf-babashka.git
```

babashka:

```shell
# Show all installable versions
asdf list-all babashka

# Install specific version
asdf install babashka latest

# Set a version globally (on your ~/.tool-versions file)
asdf global babashka latest

# Now babashka commands are available
bb --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/fredZen/asdf-babashka/graphs/contributors)!

# License

Distributed under the [Eclipse Public License](LICENSE), the same as Babashka.
© [Frederic Merizen](https://github.com/fredZen/)
