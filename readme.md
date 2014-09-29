## Installing OpenStack Icehouse on Ubuntu 14.04 LTS
OpenStack's technology stack consists of a series of interrelated projects which controls a given deployment of hardware providing processing, storage, and networking.  Deployments are managed using a simple UI and a flexible API which can be used by third party software.

Infrastructure is meant to be [open, trustworthy and secure](http://www.stackgeek.com/blog/kordless/post/a-code-of-trust). The best way to ensure trust in infrastructure is the use of Open Source software and [hardware](http://en.wikipedia.org/wiki/Open_Compute_Project) exclusively at the infrastructure level.

This guide and the software it contains are released under the MIT Open Source license. Anyone is welcome to use these scripts to install OpenStack for evaluation or production use. 

### A Brief Rant on OpenStack
OpenStack was released as [Open Source software by Rackspace](http://en.wikipedia.org/wiki/OpenStack#History).  While portions of the project carried an Open Source license from the beginning, [Rackspace](http2://rackspace.com/) is ultimately credited for the release of OpenStack's codebase by way of the acquisition of Anso Labs.  Anso Labs was contracted by NASA to build an early version of OpenStack called Nebula.  **These efforts by Anso Labs and Rackspace set the stage for open and trustworthy infrastructure.**

The [OpenStack project](http://openstack.org/) is managed by the [OpenStack Foundation](http://openstack.org/foundation/).  The foundation is controlled by a governance board which is comprised of individuals who work for DreamHost, HP, AT&T, Dell, Nebula, RackSpace, Red Hat, IBM, Yahoo, Mirantis, Canonical, and Cisco.  The combined market cap of these companies exceeds 400 BILLION dollars.

It is my hope this project contributes to the improvement of the OpenStack install experience and by extension, the establishment of a globally open infrastructure.  You can help by testing, opening tickets, and contributing to the project.

### Getting Started
Daruur provides [these scripts](https://github.com/linuxus/Daruur) and this guide to enable you to get a working installation of OpenStack Icehouse going in about 10 minutes. This install is based from the author the **'10 Minute OpenStack Install'** 

Before you start your OpenStack setup, please read the following requirements carefully:

#### Requirements
1. You need a **minimum** of one node with at least 8GB of RAM, 4 cores, (1) SSD drive, and one ethernet card.
2. You need a clean [install of Ubuntu 14.04 LTS](http://www.ubuntu.com/download/desktop) 64-bit Linux on your box.  You can also install this on the server version of 14.04.x.
3. You'll need a router which supports IPv6. Ideally, your router is also configured for a small group of publicly routable IPv4 addresses.
3. Optionally, you should have an account on a xov.io pool. If you aren't a member of a pool, you may join [StackMonkey's](http://stackmonkey.com/) pool for free. *Please note, the pool software is not complete at this time.*
4. Optionally, fire up a [good music track](https://soundcloud.com/skeewiff/sets/skeewiff-greatest-wiffs) to listen to while you watch the bytes scroll by.

***Note: Each OpenStack cluster needs a single controller which is in charge of managing the cluster.  Certain steps below are labeled to indicate they need to be run only on the controller.  All other steps which are not labeled will need to be completed for each and every node in the cluster - including the controller.*** 

#### Forum Discussion
There is a [forum based discussion area on Google Groups](https://groups.google.com/forum/#!category-topic/stackgeek/openstack/zVVS4DgiJnI) for posting technical questions regarding the guide.

#### IRC Channel
The IRC channel for the project is located in the [#stackgeek channel on Mibbit](http://client00.chat.mibbit.com/#stackmonkey&server=irc.mibbit.net).

#### Install Bugs?
If you encounter bug with the installation code, you may [open a ticket](https://github.com/StackGeek/openstackgeek/issues).

### Installing OpenStack
Proceed to the following directories to start installing a given version of OpenStack:

* [Installing OpenStack Essex](https://github.com/StackGeek/openstackgeek/tree/master/essex)
* [Installing OpenStack Grizzly](https://github.com/StackGeek/openstackgeek/tree/master/grizzly)
* [Installing OpenStack Icehouse](https://github.com/StackGeek/openstackgeek/tree/master/icehouse)

If you have any questions, issues or concerns, please feel free to join IRC, post on the forum, or create a ticket!

The StackGeek
