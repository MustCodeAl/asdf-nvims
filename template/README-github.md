<div align="center">

# asdf-nvims [![Build](https://github.com/MustCodeAl/asdf-nvims/actions/workflows/build.yml/badge.svg)](https://github.com/MustCodeAl/asdf-nvims/actions/workflows/build.yml) [![Lint](https://github.com/MustCodeAl/asdf-nvims/actions/workflows/lint.yml/badge.svg)](https://github.com/MustCodeAl/asdf-nvims/actions/workflows/lint.yml)

[nvims](https://github.com/Traap/nvims/blob/master/nvims) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add nvims
# or
asdf plugin add nvims https://github.com/MustCodeAl/asdf-nvims.git
```

nvims:

```shell
# Show all installable versions
asdf list-all nvims

# Install specific version
asdf install nvims latest

# Set a version globally (on your ~/.tool-versions file)
asdf global nvims latest

# Now nvims commands are available
<TOOL CHECK>
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MustCodeAl/asdf-nvims/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [MustCodeAl](https://github.com/MustCodeAl/)
