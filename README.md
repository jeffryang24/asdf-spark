<div align="center">

# asdf-spark [![Build](https://github.com/jeffryang24/asdf-spark/actions/workflows/build.yml/badge.svg)](https://github.com/jeffryang24/asdf-spark/actions/workflows/build.yml) [![Lint](https://github.com/jeffryang24/asdf-spark/actions/workflows/lint.yml/badge.svg)](https://github.com/jeffryang24/asdf-spark/actions/workflows/lint.yml)


[spark](https://spark.apache.org/docs/latest/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add spark
# or
asdf plugin add spark https://github.com/jeffryang24/asdf-spark.git
```

spark:

```shell
# Show all installable versions
asdf list-all spark

# Install specific version
asdf install spark latest

# Set a version globally (on your ~/.tool-versions file)
asdf global spark latest

# Now spark commands are available
spark --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jeffryang24/asdf-spark/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jeffry Angtoni](https://github.com/jeffryang24/)
