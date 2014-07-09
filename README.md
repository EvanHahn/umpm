umpm, a simple package manager for the University of Michigan's CAEN
====================================================================

If you want to install packages on CAEN, enter umpm. No sudo needed!

Installation is one line:

```sh
curl -sSL https://raw.githubusercontent.com/EvanHahn/umpm/master/install | bash
```

Usage is pretty simple:

```sh
# what can we install?
umpm list
umpm search node

# how do we install a package?
umpm install node

# how do we unininstall a package?
umpm uninstall node

# how do we uninstall umpm completely?
umpm implode
```
