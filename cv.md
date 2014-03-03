## Details ##

* Full name: Robert Walker
* Date of birth: 22 October 1977
* Nationality: British
* E-mail: bob@randomness.org.uk
* Phone: 07810 542 241
* Address: 19 Clarendon Road, Croydon, CR0 3SJ

## Skills ##

* Operating Systems: Linux (Ubuntu, Debian, Red Hat), Solaris, FreeBSD, OpenBSD, OS/2
* Configuration Management: Chef, Puppet, CFEngine2
* Version Control: Git, SVN, CVS, RCS
* Monitoring and Metrics: Nagios, Icinga, Graphite, Ganglia, Munin, StatsD, Diamond
* Shell Scripting: bash
* Packaging: deb, RPM, SRV4
* Agile Methodologies: Kanban, Scrum, Continous Integration/Deployment
* Databases: MySQL, PostgreSQL

## Employment History ##

### February 2013 – Present: WebOps for [Government Digital Service][]

### October 2010 – February 2013: Systems Architect for [TagMan][]

At TagMan I was responsible for maintaining and growing a platform serving approximately two billion hits a month spread over six points of presence across the world. During my time at TagMan I worked both in the Operations Team and in a development team focused on improving the scalability of our architecture.

As part of the Operations Team, I introduced the concept of
configuration management with an initial install of Puppet, and later
supported a switch to Chef by writing cookbooks and managing the
contractor who did the bulk of the work.  I also acted as team leader
during periods when we had no Operations Director.

My scalability work included identification of the inherently
non-scalable parts of the codebase, helping the developers design
replacement code with an eye to scalability, and liaising with product
management during addition and prioritisation of the necessary tasks
in the backlog.  I replaced our legacy system of client configuration
(which used a MySQL replication chain) with a more scalable solution
based on Git and message queues.  I also replaced our in-house
deployment tool with a system of packages and Chef cookbooks, both to
improve scalability and to bring our procedures closer to industry
standards.

### March 2008 – October 2010: Senior Systems Administrator for Ominor

At Ominor I set up and maintained over 30 servers for a range of e-commerce
websites developed in PHP and Ruby on Rails, spread across two data centres
in several environments. One of my major tasks was to provision a new rack
for a client with a turnover of approximately one million pounds a month. I
managed the servers with Puppet, and used Nagios and Munin to monitor the
servers and collect usage data.

Throughout my time at Ominor I worked closely with the developers as part
of a team following an Agile methodology. As part of this I helped maintain
the continuous integration servers, and performed deploys as and when they
were signed off by the clients.


### January 2008 – March 2008: Contract Systems Administrator for Fotango

During the windup of Fotango, I worked as a contractor providing out-of-hours
cover and daytime support while the Fotango systems were transitioned to
their new provider.

### January 2006 – December 2007: Senior Systems Administrator for Fotango

At Fotango I was a member of a five-person team providing support for about
200 Red Hat and Debian machines in our production, staging, development and
office environments.

One of my first tasks was to design and install a rack for a new product,
including redundant routers, load balancers, web servers and database
servers. The routers used VRRP for failover, and the load balancers used a
combination of Heartbeat, ldirectord and IPVS to provide high-availability
web services. The database cluster ran PostgreSQL, and used DRBD and
Heartbeat to provide a failover solution. I also set up monitoring and
logging for this product using Nagios and syslog-ng. The web servers were
organized as Xen guest domains spread across a cluster of machines.

I was also responsible, along with a co-worker, for investigating
alternative technologies for automatic provisioning of machines, to replace
the existing system based on CFEngine and a custom autoinstaller. Much of
our testing involved virtualization using Xen and VMware. Our eventual
choice was a combination of Puppet and FAI.

As well as projects such as these, I was part of the on-call rota providing
support for our legacy systems, including our IBM SAN and several large
MySQL databases.

### August 2002 - December 2005: Senior Systems Administrator for [Glu Mobile][]

While at Glu Mobile I installed and  maintained  over  20  internal  and
external systems which provided numerous services.  My  main  duty  was  the
administration of six Sun machines (3x280R, 3xv100)  running  Solaris  which
acted as a provisioning system for mobile games using  Jboss  and  MySQL.  I
also administered machines running other services such as mail,  DNS,  Samba
for internal  file  shares,  Checkpoint  FW-1/VPN-1,  HTTP  (both  barebones
Apache/PHP  and  Jboss/Jetty  solutions)   and   DHCP.   I   installed   and
administered a new backup system using Veritas NetBackup 4.5 and a  Sun  L8,
and initiated the process of migrating to Veritas NetBackup 6.0 with  a  Sun
L100.  For most of my time  at  Glu  I  was  also  responsible  for  desktop
support.

### August 2000 - June 2002: Systems Administrator for [Profero][]

At Profero I was responsible for the administration of  several  Intel-based
machines running FreeBSD, OpenBSD and Suse Linux.  These  machines  provided
services such as mail, DNS and file sharing using  Samba  and  AppleTalk.  I
also administered  the  machines  that  Profero's  ad  servers  ran  on.  In
conjunction with this I set up and maintained a firewall  (StoneGate)  which
provided load balancing and clustering.

### June 2000 - July 2000: Fixed-term contract to provide support and systems administration for [Sciteb][]

While contracting for Sciteb I installed a number of desktops (Linux and
Windows) and set up several services on their Linux server.

### August 1999 - June 2000: Systems Administrator and Software Developer for Pepper Head Design

I joined Pepper Head Design as an HTML coder and progressed to become a  PHP
and JSP developer leading a team of two other  developers.  I  also  liaised
with our outsourced Java developers, and  was  responsible  for  support  of
desktops and servers running a combination of Linux, OS/2 and Windows.

[sciteb]: http://www.sciteb.com "Sciteb"
[profero]: http://www.profero.com "Profero"
[tagman]: http://eu.tagman.com "TagMan"
[glu mobile]: http://www.glu.com "Glu Mobile"
[government digital service]: https://www.gov.uk/government/policy-teams/government-digital-service "Government Digital Service"
