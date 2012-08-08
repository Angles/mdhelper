Fork of __mdhelper__ to remind me, put a fork in it
---------------------------------------

Status as _mdhelper_ as of July 16, 2012.
----------


* __broken__.


* __will not be fixed__ &quot;_anytime soon_&quot;


## &quot;... full rewrite. Not likely ...&quot;
The __mdhelper__ [GitHub repo](https://github.com/erica/mdhelper) had an issue called [&quot;Broken?&quot;](https://github.com/erica/mdhelper/issues/1). One person said it &quot;shows no files when i use _-list_ &quot; others said, broken with 10.6.6 and Lion.


On July 16, 2012 [Erica](http://ericasadun.com) [Sadun](https://github.com/erica) closed the issue [with comment](https://github.com/erica/mdhelper/issues/1#issuecomment-7021822) &quot;_I&#x27;d have to do a full rewrite. Not likely with time constraints any time soon... Sorry. :(_ &quot;.


# [mdhelper](https://github.com/erica/mdhelper) is [b0rked](https://github.com/erica/mdhelper/issues/1#issuecomment-7021822).


* __Bummer__: It&#x27;s Broken.


* This is a __fork__ for one purpose:  Everyone __forks__ each other on GitGub. Yes, __a noob__ can learn to __fork__, it's not the size of the repo, __forking__ too much looks big, I will not do that. __I fork reasonable__, starting slow, leave size to elite professionals, _forking_ for money. Some may never be so large, but __think positive!__


* oh yeah, and these are notes to me, to put them here.


* these are my notes to me, I loose things. Here, I may have committed them.


* The real [mdhelper](https://github.com/erica/mdhelper) by the legendary [Erica](https://github.com/erica) [Sadun](http://ericasadun.com/) is [over here](https://github.com/erica/mdhelper).


* Note to self: read something in that thick _hardcopy_ of __iOS5 Cookbook__ I bought, check her repo of [example code](https://github.com/erica/iOS-5-Cookbook). Get _less_ clueless, and __think positive__!


* There is 0.00% change of anyone seeing any thing I put here. I can say whatever.


__In the unlikely event someone stumbled here__, ___KNOW THIS:___ [__YOU NEED HELP__](https://help.github.com/). No one reads this, don't be stupid. __RUN IN THE OPPOSITE DIRECTION, THAT IS AN ORDER__.


Yes I tried it, it is broken. First I knew of it. Before that, I pasted a lot of stuff, notes, from some blog, here they are. Why delete good copy and paste?


## Before I knew it was broken, I took these notes. Deleting hurts.


Copy and paste of an old summary of ___usage___ from a post on [devicegadget](http://www.devicegadget.com/iphone/backup-iphone.html) from May 9, 2011 __uses the old short commands__. The information, _unknown reliability_, but [__the blog__](http://www.devicegadget.com/iphone/backup-iphone.html) __looks cool and expert__. &#x28; The source code shows the help info changed, maybe this was useful once : &#x28;



``` bash
$ ./mdhelper

Usage: mdhelper options
-h		Print this message and exit
-d		Show the backup directory
-l		List contents for each platform
-L		List the summary for each platform
-f		List all files and mdbackup names for each platform
-m		Extract all available manifests
-X	phrase	Extract all files where the device name starts with the match phrase
-C	phrase	Extract all files containing the phrase in the original filename
-M	phrase	Extract all mdbackups whose name contains the match phrase
-x	files		Extract each mdbackup file listed by path
```


The Site gives several examples:


* To extract databases for sMs ... and notes ...:


    `./mdhelper -C sms.db`


* extracts all the property lists, which contain bookmarks ... and map bookmarks.


    `./mdhelper -C .plist`


* extracts sQlite databases, which contain address Book ... and calendar ... data:


    `./mdhelper -C .sqlitedb`


## THEN, I tried it, it does nothing.

