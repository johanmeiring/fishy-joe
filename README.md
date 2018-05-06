# fishy-joe

[![Software License](https://img.shields.io/badge/License-MIT-orange.svg?style=flat-round)](https://github.com/johanmeiring/awesomeminer-go-sdk/blob/master/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-round)](https://fishshell.com)
[![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-round)](https://www.github.com/oh-my-fish/oh-my-fish)

A theme for [Oh My Fish](https://www.github.com/oh-my-fish/oh-my-fish).

## Install

```fish
$ omf install https://github.com/johanmeiring/fishy-joe
...
```

## Configuration

This theme uses Fish's built-in `__fish_git_prompt` function, and as such the Git portion of the prompt can be customised as per [http://mariuszs.github.io/blog/2013/informative_git_prompt.html](http://mariuszs.github.io/blog/2013/informative_git_prompt.html).   My settings in `~/.config/fish/config.fish` (or alternatively `~/.config/omf/init.fish`) are currently as follows:

```fish
set __fish_git_prompt_show_informative_status 'yes'
set __fish_git_prompt_showdirtystate 'yes'
set __fish_git_prompt_showstashstate 'yes'
set __fish_git_prompt_showuntrackedfiles 'yes'
set __fish_git_prompt_showupstream 'yes'
set __fish_git_prompt_showcolorhints 'yes'
set __fish_git_prompt_color_branch yellow
set __fish_git_prompt_color_upstream_ahead green
set __fish_git_prompt_color_upstream_behind red
set __fish_git_prompt_color_branch_dirtystate red
set __fish_git_prompt_color_branch_cleanstate green
```

## License

This SDK is distributed under the MIT License.  See the LICENSE file for more details.

## Donations

Donations are very welcome, and can be made to the following addresses:

* BTC: 1AWHJcUBha35FnuuWat9urRW2FNc4ftztv
* ETH: 0xAF1Aac4c40446F4C46e55614F14d9b32d712ECBc
