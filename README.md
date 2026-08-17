# initpoly
Nethack 3.6.0 initpoly patch

Idea from r.g.r.n, implemented by bd (from r.g.r.n), ported to 3.6.0 by BugsBunnySan.

This patch allows one to select a non-default form when starting the game. With all the benefits and drawbacks that comes with. This form does not time out, rhater, it becomes your normal form.

You can also 'grow up', ala baby dragon -> dragon, or kitten -> housecat.This works both on your true form and a polymorphed form, even both at once.

You can, of course, still polyself into another form later in the game.

Apply the patch to the nethack 3.6.0 sources, by being in the nethack-3.6.0/ directory and running
#>patch -p1 < /path/to/initpoly-3.6.0.patch

3.4.1 patch retrieved via the wayback machine (web.archive.org), originaly from:
http://bd-home-comp.no-ip.org/initpoly
and ported to 3.6.0

Historicaly from a discussion on rec.games.roguelike.nethack:

https://groups.google.com/forum/#!searchin/rec.games.roguelike.nethack/initpoly|sort:relevance/rec.games.roguelike.nethack/b-ezWumIOr4/a-wsMDQ01lgJ

(and search for initpoly in that newsgroup)
