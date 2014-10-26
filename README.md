# dotfiles

This is a collection of my dotfiles for Mac OS X. Borrows some things from [mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles) and [gcollazo/dotfiles](https://github.com/gcollazo/dotfiles).

## Install

`install.sh` will bootstrap dotfiles and run initial setup after a fresh install. Before running this it's a good idea to install Xcode from the App Store and install any pending system updates. This runs `bootstrap.sh`.

```
git clone git@github.com:jpadilla/dotfiles.git
cd dotfiles
./install.sh
```

## Bootstrap

`boostrap.sh` will bootstrap dotfiles into your home directory by creating symlinks. Run with `--force` to overwrite if files already exist.

## My OS X Setup

### App Store

- [Xcode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12)
- [1Password](https://itunes.apple.com/us/app/1password-password-manager/id443987910?mt=12)
- [Navicat Premium Essentials](https://itunes.apple.com/us/app/navicat-premium-essentials/id466416967?mt=12)
- [TweetDeck](https://itunes.apple.com/us/app/tweetdeck-by-twitter/id485812721?mt=12)
- [Pages](https://itunes.apple.com/us/app/pages/id409201541?mt=12)
- [Keynote](https://itunes.apple.com/us/app/keynote/id409183694?mt=12)
- [Numbers](https://itunes.apple.com/us/app/numbers/id409203825?mt=12)

### Browsers

- [Chrome](https://www.google.com/chrome/browser/)
- [Firefox](https://www.mozilla.org/en-US/firefox/desktop/)

### Fonts

- [Inconsolata](http://levien.com/type/myfonts/inconsolata.html)
- [Source Code Pro](http://sourceforge.net/projects/sourcecodepro.adobe/files/)

### Sublime Text 3

- [Package Control](https://sublime.wbond.net/installation)
- SideBarEnhancements
- SublimeLinter
- SublimeLinter-flake8
- SublimeLinter-jshint
