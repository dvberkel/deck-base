Deck Base
=========

*Deprecated:* This project is deprecated in favor of [generator-deckjs][].

[deck.js][deck] is a great tool for creating modern HTML
presentation. Overtime I created a custom set of tools. 
This project can be used as a starting point for the creation
of a custom presentation.

Getting Started
---------------

Create a git repository, add this repository as a remote, fetch the content
and merge the master branch.

    mkdir example-presentation
    cd example-presentation
    git init
    git remote add base git://github.com/dvberkel/deck-base.git
    git fetch base
    git merge origin/master

The repository uses submodules which need to be correctly initialized.

    git submodule init
    git submodule update

[deck]: http://imakewebthings.com/deck.js/ "Homepage of deck.js"
[generator-deckjs]: https://github.com/dvberkel/generator-deckjs
