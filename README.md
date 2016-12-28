# Sublime Settings and Packages

Ok, I know what your thinking...

````Are you really going to use a git repo to manage your Sublime Text install?````

**YES!**

I live in a multi-machine, multi-environment world, and quite frankly I like to have the same settings across devices and operating systems. This is the quickest and easiest way for me to do that. 

## Quick Start

### Linux

    git clone git@github.com:JeremyCade/sublime_settings.git
    cd sublime_settings
    mv .git .gitignore README.md $HOME/.config/sublime-text-3/
    mv Packages/ $HOME/.config/sublime-text-3/
    cd ..
    rm -rf sublime_settings

### OS X

   git clone git@github.com:JeremyCade/sublime_settings.git
   cd sublime_settings
   mv .git .gitignore README.md "$HOME/Library/Application Support/Sublime Text 3/"
   rm -rf "$HOME/Library/Application Support/Sublime Text 3/Packages/"
   mv "Install Packages" Packages "$HOME/Library/Application Support/Sublime Text 3/"
   rm -rf submlime_settings


## Checkout Locations

### Windows
On Windows this repository should be cloned to: 

    %USERPROFILE%\AppData\Roaming\Sublime Text 3\

### Ubuntu
On Ubuntu this repository should be cloned to:

    $HOME/.config/sublime-text-3/
