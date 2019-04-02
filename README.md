# macports_update

A little script to ease the process of updating MacPorts.

Usually, you have to run multiple commands to complete the whole process of updating MacPorts, upgrading the outdated packages, and then cleaning up any residual stuff laying around. The goal of this script is to ease that process, albeit it is currently tailored to my own preferenes.

# Usage

```
$ macports_update -h
Usage: macports_update [options]
    -u, --update-only                Only updates MacPorts, doesn't clean anything
    -c, --cleanup                    Cleans old program versions and such
```

Running it without any options does the whole thing; it updates MacPorts and cleans up. This is usually what I want to do, so I wanted the simplest case of no options to just do everything.

# License

This is licensed under a BSD-3 license. See [COPYING.md](./COPYING.md)