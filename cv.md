* Full name: Robert Walker
* Date of birth: 22 October 1977
* Nationality: British
* E-mail: bob@randomness.org.uk
* Twitter: [@rjw1](https://twitter.com/rjw1)
* Phone: 07810 542 241
* Address: 19 Clarendon Road, Croydon, CR0 3SJ

I am a senior operations engineer with over 17 years of experience in multiple
environments using a wide range of Unixes (Linux, BSD and Solaris),
configuration management tools (Puppet, Chef and CFengine2) and platforms (AWS,
vCloud and bare metal) while supporting applications in a variety of languages
(Ruby, Perl, Python, Java and Go). I can help infrastructure teams to define a
product road map both as a technical lead and as a product owner.

I have been practicing DevOps since before the term was coined, and was an
organizer of DevOpsDays London 2017. I have opinions on continuous integration
and continuous deployment of both applications and infrastructure. I also
believe in HumanOps, and have spoken several times about how on call should not
be a burden to the people involved.

### Talks

* [What should wake you up at night? - London Devops #30](https://www.youtube.com/watch?v=MumyrGQMAJY)
* [How GOV.UK does on call - HumanOps London May 2016](https://www.youtube.com/watch?v=XpGvssf3t50&feature=youtu.be)


## Employment History ##

### February 2016 – present: Head of Web Operations for [Government Digital Service][]

As head of the Web Operations community at GDS, I worked with the other
technical heads of community to look after our community members. I provided
mentorship and line management to around 20 other engineers, and made sure they
were learning and developing. I empowered the community to self-organise events
and to share learnings between teams, and I also helped organise several
off-site events.

I participated in the government-wide Digital, Data and Technology (DDaT) effort
to define a career path for people within the software engineering community. My
position as the main point of contact for recruitment of Web Operations
engineers within GDS helped me realise that this was a burden that needed to be
shared, and so I created a rota of people to be main contact week-to-week.

After a decision was made to change how we managed platforms, I was part of the
team which enabled this transition. My main roles were liaising with my
community and helping to define the work that the new central teams would do
along with the existing product managers and delivery managers.

While Head of Web Operations, for a time I was also the product manager for the
GOV.UK infrastructure team and participated in the planning for the whole of
GOV.UK. I worked with the Government PaaS team on planning the migration of
GOV.UK to the government PaaS.

### December 2014 – January 2016: Senior Web Operations Engineer for [Government Digital Service][]

As a senior engineer on the GOV.UK infrastructure team, I worked with technical
architects and senior developers to define the technical direction of GOV.UK. I
continued to work on several large projects which provided the foundation for
migrating us to a different hosting provider. I eventually became the technical
lead and product owner for the team, helping to set our direction and make
technical decisions. I also helped to mentor our new staff members.

During this period, I was made Acting Head of Web Operations, at which point I
relinquished my tech lead post but continued to manage the product. 

### February 2013 – November 2014: Web Operations Engineer for [Government Digital Service][]

I joined GDS as a member of the Infrastructure and Tools team within GOV.UK. I
worked on several major projects including migrating
[GOV.UK](https://www.gov.uk) to a [new
platform](https://gdstechnology.blog.gov.uk/2014/03/28/migrating-govuk-infrastructure/),
leading technically on the setting up of a new logging infrastructure and
helping with the procurement of a new CDN. I managed the team's backlog when we
lacked a delivery manager, and facilitated several retrospectives. I
participated fully in our second line support model and out of hours on call
rota, and trained several of our developers so that they could contribute to
second line support. I also helped maintain several environments and Puppet
repositories.

### October 2010 – February 2013: Systems Architect for [TagMan][]

At TagMan I was responsible for maintaining and growing a platform serving
approximately two billion hits a month spread over six points of presence across
the world. During my time at TagMan I worked both in the Operations Team and in
a development team focused on improving the scalability of our architecture.

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
[government digital service]:
https://www.gov.uk/government/policy-teams/government-digital-service
"Government Digital Service"
