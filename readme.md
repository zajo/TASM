# Borland Turbo Assembler Installation

This repo contains pre-installed binaries for:

* Turbo Assembler 4.1
* Turbo Linker 7.1
* Borland Make 4.0

This was created from the official distribution diskettes of Turbo Assembler. To use it, boot [DOSBOX](https://www.dosbox.com/) and type:

```
mount c <TASM-REPO-ROOT-PATH>
PATH=Z:\;C:\BIN
```

The first command mounts the contents of this repo as drive C in DOSBOX. The second command places the bin directory on the path.

Voila, you're ready to assemble and link under DOSBOX.

# OK, but WHY?

Recently I dug up my old disks and recovered the [source code for Appler](https://github.com/zajo/appler), an Apple ][ emulator me and a buddy of mine wrote in the early 1990s. I thought it'd be nice to get it to build from source again. :)