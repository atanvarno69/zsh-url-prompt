# zsh url prompt

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://github.com/atanvarno69/zsh-url-prompt/blob/master/LICENSE)
[![Latest Version](https://img.shields.io/github/release/atanvarno69/zsh-url-prompt.svg?style=flat-square)](https://github.com/atanvarno69/zsh-url-prompt/releases)

A URL-style prompt.

# Requirements

-  [zsh](https://www.zsh.org) >= 5.8

# Installation

Clone this repo:

```sh
git clone https://github.com/atanvarno69/zsh-url-prompt.git
```

To install locally as a user, copy or symlink `prompt_url_setup` to somewhere in your
[`$fpath`](https://zsh.sourceforge.io/Doc/Release/Parameters.html#index-fpath).

To install globally as root, copy or symlink `prompt_url_setup` to `/usr/share/zsh/Prompts`.

# Usage

Then to initialize, add this to your `.zshrc`:

```zsh
autoload -Uz promptinit; promptinit
prompt url
```

You can preview the prompt with:

```zsh
prompt -p url
```

## Customization

Each element of the prompt can be disabled or its color changed. You can see all the customization options with:

```zsh
prompt -h url
```

See the [zsh documentation](https://zsh.sourceforge.io/Doc/Release/Zsh-Line-Editor.html#Character-Highlighting) for
valid color options.
