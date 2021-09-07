# Borland Turbo Assembler Installation

This repo contains pre-installed binaries for:

* Turbo Assembler 4.1
* Turbo Linker 7.1
* Borland Make 4.0

This was created from the official distribution disks of Turbo Assembler. To use it, boot [DOSBOX](https://www.dosbox.com/) and type:

```
mount t <TASM-REPO-ROOT-PATH>
PATH=%PATH%;T:\BIN
```

The first command mounts the contents of this repo as drive `T` in DOSBOX. The second command places the `BIN` directory on the system path.

Voila, you're all set to assemble and link DOS programs under DOSBOX.

You're probably thinking: "Great! I am dying to build a DOS program written in 8086 assembly! Do you have one of these puppies I can play with?"

I knew you'd ask this, and this is your lucky day! Recently (or not, depending on when you read this) I dug up my old disks and recovered the [source code for Appler](https://github.com/zajo/appler), an Apple ][ emulator me and a buddy of mine wrote in the early 1990s. Who knows, maybe you'll do something cool with it and send me a pull request. :)