# JM's dotfiles.

Now compiled mostly from [Paul Irish](https://github.com/paulirish/dotfiles) and [Mathias Bynens](https://github.com/mathiasbynens/dotfiles/)'s dotfiles with some minor customization.

## Private Config

Toss it into a file called `.extra` which you do not commit to this repo and just keep in your `~/`

## Syntax Highlighting

…is really important. even for these files.

add the below to this file: `~/Library/Application Support/Sublime Text/Packages/ShellScript/Shell-Unix-Generic.tmLanguage`

```xml
<string>.aliases</string>
<string>.bash_profile</string>
<string>.bash_prompt</string>
<string>.bashrc</string>
<string>.exports</string>
<string>.functions</string>
<string>.git</string>
<string>.gitattributes</string>
<string>.gitconfig</string>
<string>.inputrc</string>
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

#### git, brah
* `.git`
* `.gitattributes`
* `.gitconfig`
* `.inputrc` - config for bash readline


## Installation

```bash
git clone https://github.com/jorgemancheno/dotfiles.git && cd dotfiles && ./sync.sh
```

To update later on, just run the sync again.
