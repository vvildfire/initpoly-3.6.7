# initpoly
Nethack 3.6.7 initpoly patch

Idea from r.g.r.n, implemented by bd (from r.g.r.n), ported to 3.6.0 by BugsBunnySan and then to 3.6.7 by vvildfire.

This patch allows one to select a non-default form when starting the game, with all the benefits and drawbacks that comes with. This form does not time out; rather, it becomes your new base form.

You can also 'grow up', e.g. baby dragon -> dragon, or kitten -> housecat. This works both on your true form and a polymorphed form, and even both at once.

You can, of course, still polyself into another form later in the game. For silver-hating forms and forms without hands, doing so is necessary to complete the game.

Available in both patch and binary ("ready-to-run") form.

Apply the patch to the nethack 3.6.7 sources by being in the nethack-3.6.7/ directory and running
#>patch -p1 < /path/to/initpoly-3.6.7.patch

3.4.1 patch retrieved via the wayback machine (web.archive.org), originally from:
http://bd-home-comp.no-ip.org/initpoly

3.6.0 port created by BugsBunnySan accessed from:
https://github.com/BugsBunnySan/initpoly
and ported to 3.6.7 by me. :)

Historically from a discussion on rec.games.roguelike.nethack:

https://groups.google.com/forum/#!searchin/rec.games.roguelike.nethack/initpoly|sort:relevance/rec.games.roguelike.nethack/b-ezWumIOr4/a-wsMDQ01lgJ

(and search for initpoly in that newsgroup)
