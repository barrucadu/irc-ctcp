**This project is essentially abandonware!**

I may respond to minor issues, like version bounds which need
changing, but I won't be doing any significant work.

Offer to take over the package if you want any significant changes.

[irc-ctcp][]
=========

A CTCP encoding and decoding library for IRC clients.

 - Follows [this specification][ctcpspec].

 - Doesn't implement "CTCP-level quoting", allowing multiple CTCPs to
   be embedded in a single PRIVMSG/NOTICE, as no current clients
   appear to support that.

Note
----

This used to be a part of [yukibot][], so if you want the history from
before this was split out into its own library, check there.

Contributing
------------

Bug reports, pull requests, and comments are very welcome!

Feel free to contact me on GitHub, through IRC (#haskell on freenode),
or email (mike@barrucadu.co.uk).

[irc-ctcp]: https://hackage.haskell.org/package/irc-ctcp
[ctcpspec]: http://www.irchelp.org/irchelp/rfc/ctcpspec.html
[yukibot]:  https://github.com/barrucadu/yukibot
