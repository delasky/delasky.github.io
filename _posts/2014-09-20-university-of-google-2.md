---
layout: post
title: University of Google Part 2
---

MORE recent searches with annotations!

_Searched for [configuration_spec.rb](https://www.google.com/search?q=configuration_spec.rb&hl=en)_

_Searched for [configuration_spec](https://www.google.com/search?q=configuration_spec&hl=en)_

_Searched for [rspec before(:suite)](https://www.google.com/search?q=rspec+before(:suite)&hl=en)_

_Searched for [rspec run command before every test in suite](https://www.google.com/search?q=rspec+run+command+before+every+test+in+suite&hl=en&safe=off)_

_Searched for [spec helper creating and dropping tables](https://www.google.com/search?q=spec+helper+creating+and+dropping+tables&hl=en)_

For the app we are working on, I'm trying to create a test environment where each time I run my tests all my tables are created afresh, loaded with some sample values, and then cleanly destroyed so that the process can be repeated. 

You can end up running a set of tests four or five times (or more!) while trying to track down a given bug, so my tables where filling up with duplicate values really quickly. I built methods to create and drop my tables and starting putting them in my spec files with before(:all) tags. The problem was around my fifth spec file, some of these before tags started conflicting with each other. So I had the bright idea that instead of just running the tests I need when I need to run them (which tbf has its own problems) I would set up a set of 'master' before hooks that would run in front of my entire suite, building me a shiny clean test environment each time I ran my tests. Like everything I do at this stage in my knowledge, this has turned into a multi-hour rabbithole. Sigh.

_Searched for [DROP TABLES postgresql](https://www.google.com/search?q=DROP+TABLES+postgresql&hl=en)_

In case you were wondering it should be 

		DROP TABLE table1name, table2name;

_Searched for [postgressql see all tables](https://www.google.com/search?q=postgressql+see+all+tables&hl=en)_

		\dt

_Searched for [the odin project](https://www.google.com/search?q=the+odin+project&hl=en)_

The odin project is a free, open source, online coding school and resource. The first article I read was very good! The guy who runs it is working out of the MakerSquare offices so he came by and introduced himself.

_Searched for [elbo room](https://www.google.com/search?q=elbo+room&hl=en)_

One of my classmates asked what my girlfriend and I do on Friday nights (lol). I've been to this bar so I looked it up. 

_Searched for [sushirito](https://www.google.com/maps/search/sushirito/@37.7881004,-122.4010895,17z)_

Lunch. Just made me want a real burrito.

_Searched for [lost all my spotify my_music last night?](https://www.google.com/search?q=lost+all+my+spotify+my_music+last+night%3F&hl=en)_

Spent a good chunk of my day yesterday reorganizing my Spotify library (or 'Your Music' as they are calling it now). When I started using Spotify I was putting every album in its own playlist for reasons that I can't really recall. It's been bothering me for a while since Spotify now has a 'Save Album' feature, and b/c you can't shuffle through every song saved in playlists like you can songs saved to 'Your Music'. So I started going through my playlists, saving albums and deleting single album playlists. When I woke up this morning none of the albums I had added were saved to my 'Your Music', and in fact many of the albums I had in there before were gone, as were almost all of my playlists, including many I had not finished processing! 9 bucks a month for a service I barely use and they do me like this, smDh. 

_Searched for [felix orphan black](https://www.google.com/search?q=felix+orphan+black&hl=en)_

Orphan black is an entertaining show, and this guy steals every scene he is in. At some point though he's gotta tell his sister and her stupid clone buddies that he has his own life to lead and can't just drop everything at their every whim.
