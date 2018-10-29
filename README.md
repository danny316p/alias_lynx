# alias_lynx
Quick alias-like tools that wrap and/or configure lynx for searching the web from the command line and making lynx more user-friendly as a general web browser. To start with, I created shortcuts for myself to use YubNub, DuckDuckGo, and DuckDuckGo bangs (trimming that extra four keystrokes seemed worth it). Gradually, this has evolved into a more general start point for using lynx like a quicker-and-dirtier version of a modern web browser, without having to deal with cruft like Facebook buttons, ad images, web trackers and excessive CSS and javascript. Should you want to use those things, I think you know where to find them, but when you don't want them, lynx is a powerful way to enjoy a faster and more private browsing experience.

All of these are shell scripts or configuration options that work with a standard lynx install - some of the choices here correct issues with outdated lynx installs, and all of them can be overridden with your own .lynxrc file.

Ironically, only one line of this repository is actually an alias, since that turned out to not be particularly useful for wrapping and configuring lynx for regular use. I've decided to keep the name anyway, since this is already used in enough places that moving/renaming the repository would create extra work.

These were originally developed for my .bashrc file, but got their own repository for the sake of convenience and portability. To use, clone the repo and add the following lines to wherever your aliases are stored (most likely .bash_aliases, .bashrc, or .zshrc):

```
# This first line may need to be configured as needed
ALIAS_LYNX_PATH=$HOME/github/alias_lynx;
if [ -f $ALIAS_LYNX_PATH/lynx_aliases ]; then
    . $ALIAS_LYNX_PATH/lynx_aliases
fi
```

Make sure that you use the correct path if you decide to keep your repository somewhere different than I do.

## License and contributions
GPLv3 has been slapped on here. You're welcome to suggest changes 
