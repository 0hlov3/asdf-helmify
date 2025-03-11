<div align="center">

# asdf-helmify [![Build](https://github.com/0hlov3/asdf-helmify/actions/workflows/build.yml/badge.svg)](https://github.com/0hlov3/asdf-helmify/actions/workflows/build.yml) [![Lint](https://github.com/0hlov3/asdf-helmify/actions/workflows/lint.yml/badge.svg)](https://github.com/0hlov3/asdf-helmify/actions/workflows/lint.yml)

[helmify](https://github.com/0hlov3/asdf-plugin-helmify) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add helmify
# or
asdf plugin add helmify https://github.com/0hlov3/asdf-helmify.git
```

helmify:

```shell
# Show all installable versions
asdf list-all helmify

# Install specific version
asdf install helmify latest

# Set a version globally (on your ~/.tool-versions file)
asdf global helmify latest

# Now helmify commands are available
helmify --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/0hlov3/asdf-helmify/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [0hlov3](https://github.com/0hlov3/)
