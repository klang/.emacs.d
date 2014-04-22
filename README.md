# Establish a sane .emacs.d with git

# Installation

    klp@ergates ~$  git clone https://github.com/klang/.emacs.d.git
    Cloning into '.emacs.d'...
    remote: Counting objects: 6, done.
    remote: Compressing objects: 100% (4/4), done.
    remote: Total 6 (delta 0), reused 6 (delta 0)
    Unpacking objects: 100% (6/6), done.
    Checking connectivity... done.

    klp@ergates ~$  cd .emacs.d/
    klp@ergates .emacs.d$  git submodule init
    Submodule 'elisp' (https://github.com/klang/elisp) registered for path 'elisp'

    klp@ergates .emacs.d$  git submodule update
    Cloning into 'elisp'...
    remote: Reusing existing pack: 1229, done.
    remote: Total 1229 (delta 0), reused 0 (delta 0)
    Receiving objects: 100% (1229/1229), 1.13 MiB | 654.00 KiB/s, done.
    Resolving deltas: 100% (416/416), done.
    Checking connectivity... done.
    Submodule path 'elisp': checked out '0d81610687bac2d3132794aab2a9dab72082a9dd'

    klp@ergates .emacs.d$  source init-soft-link.sh

After that, simply start up Emacs and everything will download and initialize.

# Versions

    - Emacs: GNU Emacs 24.3.1 (x86_64-apple-darwin, NS apple-appkit-1038.36) of 2013-03-13 on bob.porkrind.org
    - Git: git version 1.8.5.2 (Apple Git-48)
    - iTerm2: Build 1.0.0.20140112
    - OSX: Version 10.9.2 - 2.7 GHz Intel Core i7, 16GB 1600 MHz DDR3
    - Background: 7372643860_266aa3ca55_o.jpg (not really relevant)