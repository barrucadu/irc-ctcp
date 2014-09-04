# [irc-ctcp]: CTCP encoding and decoding

 - Follows [this specification][ctcpspec].

 - Doesn't implement "CTCP-level quoting", allowing multiple CTCPs to
   be embedded in a single PRIVMSG/NOTICE, as no current clients
   appear to support that.

Note: this used to be a part of [yukibot][], so if you want the
history from before this was split out into its own library, check
there.

[irc-ctcp]: https://hackage.haskell.org/package/irc-ctcp
[ctcpspec]: http://www.irchelp.org/irchelp/rfc/ctcpspec.html
[yukibot]:  https://github.com/barrucadu/yukibot
