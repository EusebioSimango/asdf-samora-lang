<div align="center">

# asdf-samora-lang [![Build](https://github.com/EusebioSimango/asdf-samora-lang/actions/workflows/build.yml/badge.svg)](https://github.com/EusebioSimango/asdf-samora-lang/actions/workflows/build.yml) [![Lint](https://github.com/EusebioSimango/asdf-samora-lang/actions/workflows/lint.yml/badge.svg)](https://github.com/EusebioSimango/asdf-samora-lang/actions/workflows/lint.yml)

[samora-lang](https://obadiaspelembe.github.io/samora-lang-docs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add samora-lang
# or
asdf plugin add samora-lang https://github.com/EusebioSimango/asdf-samora-lang.git
```

samora-lang:

```shell
# Show all installable versions
asdf list-all samora-lang

# Install specific version
asdf install samora-lang latest

# Set a version globally (on your ~/.tool-versions file)
asdf global samora-lang latest

# Now samora-lang commands are available
samora --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/EusebioSimango/asdf-samora-lang/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Eusebio Simango](https://github.com/EusebioSimango/)
