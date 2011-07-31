# dirtree.el -- Directory tree views for Emacs

## Installation

1 Install deps
2 download `dirtree.el` to your `emacs.d` directory.
3 `(require 'dirtree)`

## Usage

* `M-x dirtree RET`
* `M-x dirtree-buffer RET` -- Opens dirtree in a buffer in the current
   window.


## Eproject Integration

Opens dirtree with the root pointing at the current eproject root.

    (defun ep-dirtree ()
      (interactive)
      (dirtree-buffer eproject-root t))


## Requires

* [tree-mode](http://www.emacswiki.org/emacs/tree-mode.el)
* [windata](http://www.emacswiki.org/emacs/windata.el)
