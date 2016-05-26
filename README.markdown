[irc-ctcp][] [![Build Status][build-status]][build-log]
=========

A CTCP encoding and decoding library for IRC clients.

 - Follows [this specification][ctcpspec].

 - Doesn't implement "CTCP-level quoting", allowing multiple CTCPs to
   be embedded in a single PRIVMSG/NOTICE, as no current clients
   appear to support that.

The documentation of the latest developmental version is
[available online][docs].

Note
----

This used to be a part of [yukibot][], so if you want the history from
before this was split out into its own library, check there.

Contributing
------------

Bug reports, pull requests, and comments are very welcome!

Feel free to contact me on GitHub, through IRC (#haskell on freenode),
or email (mike@barrucadu.co.uk).

[irc-ctcp]:     https://hackage.haskell.org/package/irc-ctcp
[build-status]: https://travis-ci.org/barrucadu/irc-ctcp.svg?branch=master
[build-log]:    https://travis-ci.org/barrucadu/irc-ctcp
[docs]:         https://docs.barrucadu.co.uk/irc-ctcp
[ctcpspec]:     http://www.irchelp.org/irchelp/rfc/ctcpspec.html
[yukibot]:      https://github.com/barrucadu/yukibot
