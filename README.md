# dirtree.el -- Directory tree views for Emacs

## Installation

1. Install deps
2. download `dirtree.el` to your `emacs.d` directory.
3. `(require 'dirtree)`

## Usage

* `M-x dirtree RET`
* `M-x dirtree-in-buffer RET` -- Opens dirtree in a buffer in the current
   window.


## Eproject Integration

Opens dirtree with the root pointing at the current eproject root.

    (defun ep-dirtree ()
      (interactive)
      (dirtree-in-buffer eproject-root t))


## Requires

* [tree-mode](http://www.emacswiki.org/emacs/tree-mode.el)
* [windata](http://www.emacswiki.org/emacs/windata.el)


## License

Copyright (C) 2010 Free Software Foundation, Inc.

Author: Ye Wenbin <wenbinye@gmail.com>
Maintainer: Ye Wenbin <wenbinye@gmail.com>
Created: 09 Jan 2010
Version: 0.01
Keywords

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2, or (at your option)
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.

