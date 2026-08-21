# NetHack initpoly patch
Updated for 3.6.7.

Idea from r.g.r.n, implemented by bd (from r.g.r.n), ported to 3.6.0 by BugsBunnySan. Debugged and ported to 3.6.7 by vvildfire, with help from tfx.

This patch allows one to select a non-default form when starting the game, with all the benefits and drawbacks that comes with. This form does not time out; rather, it becomes your new base form. As such, you can still polyself into another form later in the game. For silver-hating forms and forms without hands, doing so is necessary to complete the game.

You can also 'grow up', e.g. baby dragon -> dragon, or kitten -> housecat. This works both on your true form and a polymorphed form, and even both at once. In versions prior to 3.6.7 this is bugged and only activates when level-drained, e.g. by the touch of a wraith.

Available in both patch and windows binary ("ready-to-run") form.

Apply the patch to the NetHack 3.6.7 source by being in the $Top directory of the source and running
#>patch -p1 < /path/to/initpoly-3.6.7.patch

Historically from a discussion on rec.games.roguelike.nethack:
https://groups.google.com/forum/#!searchin/rec.games.roguelike.nethack/initpoly|sort:relevance/rec.games.roguelike.nethack/b-ezWumIOr4/a-wsMDQ01lgJ

3.4.1 patch retrieved via the wayback machine (web.archive.org), originally from:
http://bd-home-comp.no-ip.org/initpoly

3.6.0 port created by BugsBunnySan accessed from:
https://github.com/BugsBunnySan/initpoly

3.6.7 port created by vvildfire link:
https://github.com/vvildfire/initpoly-3.6.7
