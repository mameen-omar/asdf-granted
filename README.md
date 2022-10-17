<div align="center">

# asdf-granted [![Build](https://github.com/mameen-omar/asdf-granted/actions/workflows/build.yml/badge.svg)](https://github.com/mameen-omar/asdf-granted/actions/workflows/build.yml) [![Lint](https://github.com/mameen-omar/asdf-granted/actions/workflows/lint.yml/badge.svg)](https://github.com/mameen-omar/asdf-granted/actions/workflows/lint.yml)


[granted](https://github.com/common-fate/granted) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add granted
# or
asdf plugin add granted https://github.com/mameen-omar/asdf-granted.git
```

granted:

```shell
# Show all installable versions
asdf list-all granted

# Install specific version
asdf install granted latest

# Set a version globally (on your ~/.tool-versions file)
asdf global granted latest

# Now granted commands are available
granted -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mameen-omar/asdf-granted/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mohamed Ameen Omar](https://github.com/mameen-omar/)
