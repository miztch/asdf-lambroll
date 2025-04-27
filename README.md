<div align="center">

# asdf-lambroll [![Build](https://github.com/miztch/asdf-lambroll/actions/workflows/build.yml/badge.svg)](https://github.com/miztch/asdf-lambroll/actions/workflows/build.yml) [![Lint](https://github.com/miztch/asdf-lambroll/actions/workflows/lint.yml/badge.svg)](https://github.com/miztch/asdf-lambroll/actions/workflows/lint.yml)

[lambroll](https://github.com/fujiwara/lambroll) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-lambroll  ](#asdf-lambroll--)
- [Contents](#contents)
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
asdf plugin add lambroll
# or
asdf plugin add lambroll https://github.com/miztch/asdf-lambroll.git
```

lambroll:

```shell
# Show all installable versions
asdf list-all lambroll

# Install specific version
asdf install lambroll latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lambroll latest

# Now lambroll commands are available
lambroll version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/miztch/asdf-lambroll/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [miztch](https://github.com/miztch/)
