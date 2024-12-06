<div align="center">

# asdf-music-gpt [![Build](https://github.com/zenobi-us/asdf-music-gpt/actions/workflows/build.yml/badge.svg)](https://github.com/zenobi-us/asdf-music-gpt/actions/workflows/build.yml) [![Lint](https://github.com/zenobi-us/asdf-music-gpt/actions/workflows/lint.yml/badge.svg)](https://github.com/zenobi-us/asdf-music-gpt/actions/workflows/lint.yml)

[music-gpt](https://github.com/gabotechs/MusicGPT) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-music-gpt  ](#asdf-music-gpt--)
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
asdf plugin add music-gpt
# or
asdf plugin add music-gpt https://github.com/zenobi-us/asdf-music-gpt.git
```

music-gpt:

```shell
# Show all installable versions
asdf list-all music-gpt

# Install specific version
asdf install music-gpt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global music-gpt latest

# Now music-gpt commands are available
musicgpt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zenobi-us/asdf-music-gpt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/zenobi-us/)
