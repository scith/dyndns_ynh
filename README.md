DynDNS for YunoHost using ddclient
----------------------------------
Warning: This YunoHost app is still in development. Use it at your own risk!

This application allows you to link your own domain name to your YunoHost server even if your IP is not fixed (for example at home).

Under the hood, this application installs and configure the package **ddclient** which will automatically send your IP to a dynamic DNS server whenever it changes.

Usage
-----
You must use a service which provides a server capable of linking your domain to your IP.

**OVH**
Login to the manager, and go to the *DynHost* tab of your domain. Create a new user.

Install the YunoHost app with the following settings:
- Domain: *your domain*
- Server: *www.ovh.com*
- Login: *domain.tld-user*
- Password
- Protocol: *dyndns2*

**Namecheap**
See instructions here: https://www.namecheap.com/support/knowledgebase/article.aspx/595/11/how-do-i-enable-dynamic-dns-for-a-domain

Then install the YunoHost app with the following settings:
- Domain: *your domain*
- Server: *dynamicdns.park-your-domain.com*
- Login: *yourdomain.com*
- Password
- Protocol: *namecheap*

**Dyn**
- Domain: *example.dyndns.org*
- Server: *members.dyndns.org*
- Login: *username*
- Password
- Protocol: *dyndns2*

**No-IP**
- Domain: *example.ddns.net*
- Server: *dynupdate.no-ip.com*
- Login: *username*
- Password
- Protocol: *dyndns2*

