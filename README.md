# _noty2

What is _noty2?
===============

_noty2 is a drop-in replacement for the rutorrent plugin _noty. It
uses the Web Notifications API instead of the jQuery plugin noty.

Why should I use this instead of just using the Notifications API?
==================================================================

The notifications API works differently under Chrome and
Firefox. Firefox will close the notification after a few seconds,
while Chrome will keep it there until it has been dismissed by the
user. _noty2 will give you identical behaviour under both platforms.
