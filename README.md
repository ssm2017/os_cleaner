os_cleaner
==========

What is that ?
==============
This is a set of bash scripts to run with cron to clean an OpenSimulator's grid database.

Why ?
=====
When a user client is crashing or when a region is crashing, some infos are not updated on the database so the result is phantom users or phantom regions.

A lot of grids like these phantoms because it is making the stats higher on some blogs but we decided to make something to reflect the reality.

How to use ?
============
Fill your ~/.my.cnf file with the grid database credentials and run these tests by cron. The frequency depends on your choice.

What else ?
===========
As usual with me, if you think that this is crap or that this is not well writen or have errors, instead of speaking around, please fill an issue to insult me or tell me what to enhance or contact me by irc.

Thanks for reading and i wish you have better grid stats :)
