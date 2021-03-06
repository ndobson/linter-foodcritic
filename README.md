linter-foodcritic
=========================

This is a [foodcritic](http://www.foodcritic.io/) provider for
[linter](https://github.com/atom-community/linter). It will be used with files
that have the [Chef syntax](https://atom.io/packages/language-chef).

## Installation
The `linter` package must be installed in order to use this plugin. If it
is not installed, please follow the instructions
[here](https://github.com/atom-community/linter).

### `foodcritic` Installation
Before using this plugin, you must ensure that `foodcritic` is installed on
your system. To install `foodcritic`, do the following:

0. Install [ruby](https://www.ruby-lang.org/).
0. Install `foodcritic` by typing the following in a terminal:
```ShellSession
gem install foodcritic
```
0. Alternatively install ChefDK which already includes `foodcritic`:
https://downloads.chef.io/chef-dk/

Now you can proceed to install the `linter-foodcritic` plugin.

### Plugin installation
```ShellSession
$ apm install linter-foodcritic
```
