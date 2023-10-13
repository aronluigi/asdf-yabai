<div align="center">

# asdf-yabai [![Build](https://github.com/aronluigi/asdf-yabai/actions/workflows/build.yml/badge.svg)](https://github.com/aronluigi/asdf-yabai/actions/workflows/build.yml) [![Lint](https://github.com/aronluigi/asdf-yabai/actions/workflows/lint.yml/badge.svg)](https://github.com/aronluigi/asdf-yabai/actions/workflows/lint.yml)

[yabai](https://github.com/koekeishiya/yabai) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add yabai
# or
asdf plugin add yabai https://github.com/aronluigi/asdf-yabai.git
```

yabai:

```shell
# Show all installable versions
asdf list-all yabai

# Install specific version
asdf install yabai latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yabai latest

# Now yabai commands are available
yabai --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/aronluigi/asdf-yabai/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Luigi Aron](https://github.com/aronluigi/)
