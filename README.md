# pogo-looker-upper
Simple webpage to look up attack types which are good against a pokemon

So... when playing Pokemon GO, there's this situation which comes up
every now and then - you're about to fight some pokemon, and you see
it's a WATER type. The app suggests a team for you to enter the fray
with, but often it's not a very strong team because it doesn't take
the defender's weaknesses into consideration.

What I normally do then is to google the defender's type, get to a web
page with a zillion ads, scroll down lots and lots where I may or may
not find a table where I look up the type. If it was type WATER, I
find out that this pokemon is weak to Fire, Ground, and Rock attacks.

Next, I re-open Pokemon GO, and search among my Pokemon for any which
has moves which belong to one of he three attacks. PoGo has a weird
search syntax, and I need to type the following:

	@1fire,@1ground,@1rock&@2fire,@2ground,@2rock

This is, needless to say, a major PITA. 

So I decided to write a little webpage which does the lookup for
me. Along the way I even learned some (very basic) javascript. Yay for
me!
