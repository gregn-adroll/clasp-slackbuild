# clasp-slackbuild
Slackbuild for clasp

This is a work-in-progress slackbuild for clasp. Any feedback is much appreciated!

The text for the description of clasp is taken from http://potassco.sourceforge.net/.
I don't know what license the information on the site is released under, or the normal
procedure for adding a description for slackbuilds.

This slackbuild is based on the autotools template from slackbuilds.org
https://slackbuilds.org/templates/autotools-template.SlackBuild

The process goes something like this:

    ./configure.sh
    cd build/release
    make
    make install
