# Gajim history reformatter and merger

This is a simple tool to parse the saved history files from the Gajim
XMPP client (as of its version 1.3.1), print them as tab-separated
CSV, and merge multiple history files (e.g. the histories of both
sides of a conversation in case part of one got lost).

If you understand Perl and like functional programming you could add
your own functionality, the program is using
[FunctionalPerl](http://functional-perl.org) as its main dependency.

## Bugs

* drops empty lines at the end of a message
* reduces multiple empty lines within a message to one?
* still unexplained line count difference of source vs. target even accounting for the above

