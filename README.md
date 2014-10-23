flymake-hlint.el
================

An Emacs flymake handler for checking Haskell source code with
[hlint][hlint].

Installation
=============

If you choose not to use one of the convenient packages in
[Melpa][melpa] and [Marmalade][marmalade], you'll need to add the
directory containing `flymake-hlint.el` to your `load-path`, and then
`(require 'flymake-hlint)`. You'll also need to install
[flymake-easy](https://github.com/purcell/flymake-easy).

You should also install [hlint][hlint] and ensure it is on your `exec-path`.

Usage
=====

Add the following to your emacs init file:

    (require 'flymake-hlint) ;; not needed if installed via package
    (add-hook 'haskell-mode-hook 'flymake-hlint-load)


[marmalade]: http://marmalade-repo.org
[melpa]: http://melpa.org
[hlint]: http://community.haskell.org/~ndm/hlint/

<hr>

[![](http://api.coderwall.com/purcell/endorsecount.png)](http://coderwall.com/purcell)

[![](http://www.linkedin.com/img/webpromo/btn_liprofile_blue_80x15.png)](http://uk.linkedin.com/in/stevepurcell)

[Steve Purcell's blog](http://www.sanityinc.com/) // [@sanityinc on Twitter](https://twitter.com/sanityinc)
