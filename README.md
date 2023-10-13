<div align="center">

# asdf-yabai [![Build](https://github.com/aronluigi/asdf-yabai/actions/workflows/build.yml/badge.svg)](https://github.com/aronluigi/asdf-yabai/actions/workflows/build.yml) [![Lint](https://github.com/aronluigi/asdf-yabai/actions/workflows/lint.yml/badge.svg)](https://github.com/aronluigi/asdf-yabai/actions/workflows/lint.yml)

[yabai](https://github.com/koekeishiya/yabai) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
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
Configure [Yabai](https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(latest-release))
```sh
If you want yabai to be managed by launchd (start automatically upon login):
  yabai --start-service

When running as a launchd service logs will be found in:
  /tmp/yabai_<user>.[out|err].log

If you are using the scripting-addition; remember to update your sudoers file:
  sudo visudo -f /private/etc/sudoers.d/yabai

Build the configuration row by running:
  echo "$(whoami) ALL=(root) NOPASSWD: sha256:$(shasum -a 256 $(which yabai) | cut -d " " -f 1) $(which yabai) --load-sa"

README: https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(latest-release)#configure-scripting-addition
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/aronluigi/asdf-yabai/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Luigi Aron](https://github.com/aronluigi/)
