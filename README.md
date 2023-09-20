<div align="center">

# asdf-ssm-session-manager-plugin [![Build](https://github.com/bradym/asdf-ssm-session-manager-plugin/actions/workflows/build.yml/badge.svg)](https://github.com/bradym/asdf-ssm-session-manager-plugin/actions/workflows/build.yml) [![Lint](https://github.com/bradym/asdf-ssm-session-manager-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/bradym/asdf-ssm-session-manager-plugin/actions/workflows/lint.yml)

[ssm-session-manager-plugin](https://github.com/bradym/ssm-session-manager-plugin) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add ssm-session-manager-plugin
# or
asdf plugin add ssm-session-manager-plugin https://github.com/bradym/asdf-ssm-session-manager-plugin.git
```

ssm-session-manager-plugin:

```shell
# Show all installable versions
asdf list-all ssm-session-manager-plugin

# Install specific version
asdf install ssm-session-manager-plugin latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ssm-session-manager-plugin latest

# Now ssm-session-manager-plugin commands are available
session-manager-plugin --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bradym/asdf-ssm-session-manager-plugin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Brady Mitchell](https://github.com/bradym/)
