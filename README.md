# The Fuck [![Build Status](https://travis-ci.org/nvbn/thefuck.svg?branch=master)](https://travis-ci.org/nvbn/thefuck) romanian version

Magnificent app which corrects your previous console command,
inspired by a [@liamosaur](https://twitter.com/liamosaur/)
[tweet](https://twitter.com/liamosaur/status/506975850596536320).

[![asciicast](https://asciinema.org/a/ar3tgn4i93xt3i4q82exy0kl9.png)](https://asciinema.org/a/ar3tgn4i93xt3i4q82exy0kl9)

## Installation [*experimental*]

On Ubuntu and OS X you can install `The Fuck` with installation script:

```bash
wget -O - https://raw.githubusercontent.com/andrei-cacio/thefuck/master/install.sh | sh - && $0
```

## Manual installation

Install `The Fuck` with `pip`:

```bash
sudo pip install thefuck
```

[Or using an OS package manager (OS X, Ubuntu, Arch).](https://github.com/nvbn/thefuck/wiki/Installation)

You should place this command in your `.bash_profile`, `.bashrc`, `.zshrc` or other startup script:

```bash
eval "$(thefuck --alias)"
# You can use whatever you want as an alias, like for Mondays:
eval "$(thefuck --alias futui)"
```

[Or in your shell config (Bash, Zsh, Fish, Powershell, tcsh).](https://github.com/nvbn/thefuck/wiki/Shell-aliases)

Changes will be available only in a new shell session.
To make them available immediately, run `source ~/.bashrc` (or your shell config file like `.zshrc`).


### Full [README](https://github.com/nvbn/thefuck/blob/master/README.md) file from the original thefuck

## License MIT
Project License can be found [here](LICENSE.md).
