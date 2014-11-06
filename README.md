ncshelld
========

Netcat Shell Daemon - a way to get a shell (e.g. bash) running as a TCP/IP network daemon listening for connections using netcat (nc).

I wrote this because I had a NAS that I had SSH access to but I kept borking up the SSH config and leaving myself without access until I could get physical access to reboot it.  The NAS had no telnet server and no compiler so I needed a way to gain access if the SSH server went down.  Hence, ncshelld was born.

Ben Kennish
<ben@kennish.net>
