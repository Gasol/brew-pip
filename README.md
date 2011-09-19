brew-pip -- install pip packages as homebrew formulas
=====================================================

`brew pip` allows you to install any pip package as a homebrew formula.

Install
-------

    brew install brew-pip

Usage
-----

    brew pip Mercurial

Setup
-----

After you install some pip packages, you will need to add Homebrew's pip path to your PYTHONPATH.

You can add something like the following to your ~/.bash_profile:

    export PYTHONPATH=$(brew --prefix)/lib/python2.7/site-packages

See Also
--------

brew-pip's half brother [brew-gem](https://github.com/josh/brew-gem).
