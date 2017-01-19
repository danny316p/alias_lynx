# alias_lynx
Quick alias-like tools for searching the web from the command line. To start with, I've created shortcuts for myself to use YubNub, DuckDuckGo, and DuckDuckGo bangs (trimming that extra four keystrokes seemed worth it).

These were developed for my .bashrc file, but get their own repository for the sake of convenience and portability. To use, add the following lines to your .bashrc:

```
if [ -f ~/github/alias_lynx/lynx_aliases ]; then
    . ~/github/alias_lynx/lynx_aliases
fi
```

Make sure that you use the correct path if you keep your repository somewhere different than I do.
