==========================
Inotify-based rsync daemon
==========================

Sample usage::

    rsync-inotify-from paths-to-monitor target-host

Where:

* ``paths-to-monitor`` is a file containing a list of paths to monitor for
  changes, one path per-line;
* ``target-host`` is the host to transfer the changed files to.

TODO
----

* Write a real ``README`` file
* Improve command-line parsing & co.
