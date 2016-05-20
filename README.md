# Install and configuration

This was tested via RANCID 3.3 running on Ubuntu 14.04LTS and 16.04LTS
installed from standard repositories.

Copy the file _rancid.types.conf_ to

  * /etc/rancid (Ubuntu and others)
  * /usr/local/etc/rancid (FreeBSD)
  * /usr/local/rancid/etc (hand-built?)

Your _router.db_ file should look like:

  * 192.168.168.254;sonicwall;up
  * 10.21.251.254;sonicwall;up
  * fw.int.example.com;sonicwall;up

Copy _sonlogin_ and _sonrancid_ to

  * /var/lib/rancid/bin (Ubuntu and others)
  * /usr/local/rancid/bin (*BSD or hand-built?)
