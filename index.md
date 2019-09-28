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
and convenient “computing environment” for me --- after all it’s my
main system at home and work, across several OSes:
[GNU/Linux](https://guix.gnu.org/), [NetBSD](https://www.netbsd.org/),
[OpenBSD](https://www.openbsd.org/), [ReactOS](https://reactos.org/)
and [FreeDOS](https://freedos.org/).  That means that all those
systems boot directly onto full-screen Emacs (most graphically), and
all my user initialization code is inside my `.emacs` (rather than
`.xsession`, `.xinitrc`, `.profile` or `.bashrc`) -- so all helper
sub-processes are managed by Emacs; my window manager is
[EXWM](https://github.com/ch11ng/exwm) (wherever possible), and I use
Emacs for everything feasible, the only exception being to resort to a
javascript-capable web-browser for sites requiring it and whose job
can’t be done with Emacs alone.

To make all packages in this archive available for installation within
your Emacs, just customize the variable `package-archives` to this
effect:

```elisp
(add-to-list 'package-archives
             ("oitofelix" . "https://oitofelix.github.io/elpa/"))
```

Then `M-x list-packages` should contain all newly available packages
from the **oitofelix** archive.

The following table list all packages available from this ELPA and
indicates whether they are available from other sources.  Although not
high-priority, I try to get them integrated into the canonical
upstream distribution chain as far as possible.


### Packages

Name | Description | MELPA | GNU ELPA | GNU Emacs |
-----|-------------|-------|----------|-----------|
[info-rename-buffer](https://github.com/oitofelix/info-rename-buffer) | Rename Info buffers to match manuals | | |


In case you are interested, I maintain this ELPA using
[elpa-deploy](https://github.com/oitofelix/elpa-deploy).

I have also contributed to other Emacs packages of which I’m not the
main author, either by creating new modules or improving existing
ones.  These are available from other sources, but I list them here
for completeness.

### Contributions

File | Package | Description | MELPA | GNU ELPA | GNU Emacs |
-----|---------|-------------|-------|----------|-----------|
[emms-volume.el](https://git.savannah.gnu.org/cgit/emms.git/tree/lisp/emms-volume.el) | [EMMS](https://www.gnu.org/software/emms/) | Auto-detect available volume mixers | X | X | |
[emms-volume-mixerctl.el](https://git.savannah.gnu.org/cgit/emms.git/tree/lisp/emms-volume-mixerctl.el) | [EMMS](https://www.gnu.org/software/emms/) | Support OpenBSD’s volume mixer | X | X | |



</div>
