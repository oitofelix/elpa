---
title: oitofelix - ELPA
description: >
  Emacs Lisp Package Archive
tags: >
  Emacs, Lisp
license: CC BY-SA 4.0
layout: oitofelix-homepage
base: http://oitofelix.github.io
#base_local: http://localhost:4000
---
<div id="markdown" markdown="1">
## Emacs Lisp Package Archive

This is an ELPA (Emacs Lisp Package Archive) comprised of packages
written by myself to serve the noble purpose of filling into the gaps
of making [GNU Emacs](https://www.gnu.org/software/emacs/) a practical
and convenient “computing environment” for me, because it’s my main
system at home and work, across several OSes:
[GNU/Linux](https://guix.gnu.org/), [NetBSD](https://www.netbsd.org/),
[OpenBSD](https://www.openbsd.org/), [ReactOS](https://reactos.org/)
and [FreeDOS](https://freedos.org/).

That means that all those systems boot directly onto full-screen Emacs
(most graphically), and all my user initialization code is inside my
`.emacs` (rather than `.xsession`, `.xinitrc`, `.profile` or
`.bashrc`) -- so all helper sub-processes are managed by Emacs; my
window manager is [EXWM](https://github.com/ch11ng/exwm) (wherever
possible), and I use Emacs for everything feasible, the only exception
being to resort to a javascript capable web-browser for sites
requiring it and whose job can’t be performed within Emacs.

To make all packages in this archive available for installation within
your Emacs, just customize the variable `package-archives` to this
effect:

```elisp
(add-to-list 'package-archives
             ("oitofelix" . "https://oitofelix.github.io/elpa/"))
```

Then `M-x list-packages` should list all newly available packages from
the "oitofelix" archive.

The table below list all packages available from this ELPA and whether
they are available from other sources.


### Packages
Name | Description | MELPA | GNU ELPA | Core Emacs |
-----|-------------|-------|----------|------------|
[info-rename-buffer](https://github.com/oitofelix/info-rename-buffer) | Rename Info buffers to match manuals | | |


I maintain this ELPA using
[elpa-deploy](https://github.com/oitofelix/elpa-deploy).

I have also contributed for other Emacs packages which I’m not the
main author thereof, either creating new modules or improving existing
ones.  These are available from other sources, but I list them here
for completeness.

### Contributions
File | Package | Description | MELPA | GNU ELPA | Core Emacs |
-----|---------|-------------|-------|----------|------------|
emms-volume-mixerctl.el | [EMMS](https://www.gnu.org/software/emms/) | Support OpenBSD’s volume mixer | X | X | |
emms-volume.el | [EMMS](https://www.gnu.org/software/emms/) | Auto-detect available mixers | X | X | |


</div>
