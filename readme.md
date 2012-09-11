# Jorge's dotfiles.

Now compiled mostly from [Paul Irish](https://github.com/paulirish/dotfiles) and [Mathias Bynens](https://github.com/mathiasbynens/dotfiles/)'s dotfiles with some minor customization.

## Private Config

Toss it into a file called `.extra` which you do not commit to this repo and just keep in your `~/`

## Syntax Highlighting

…is really important. even for these files.

add the below to this file: `~/Library/Application Support/Sublime Text 2/Packages/ShellScript/Shell-Unix-Generic.tmLanguage`

```xml
<string>.aliases</string>
<string>.bash_profile</string>
<string>.bash_prompt</string>
<string>.bashrc</string>
<string>.brew</string>
<string>.exports</string>
<string>.functions</string>
<string>.git</string>
<string>.gitattributes</string>
<string>.gitconfig</string>
<string>.gitignore</string>
<string>.inputrc</string>
<string>.osx</string>
<string>.vim</string>
<string>.vimrc</string>
```



### Sensible OS X Defaults

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
./.osx
```

## Overview of Files

#### Shell Environement
* `.aliases`
* `.bash_profile`
* `.bash_prompt`
* `.bashrc`
* `.exports`
* `.functions`
* `.extra` - not included, explained above

#### Manual Run
* `.osx` - run on a fresh osx machine

#### git, brah
* `.git`
* `.gitattributes`
* `.gitconfig`
* `.gitignore`
* `.inputrc` - config for bash readline


## Installation

```bash
git clone https://github.com/jorgemancheno/dotfiles.git && cd dotfiles && ./sync.sh
```

To update later on, just run the sync again.
