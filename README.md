RVM RPM Package
===============

RPM package for [rvm](http://rvm.beginrescueend.com/) suitable for CentOS or
RHEL.


About
-----

From the package description:

RVM is the Ruby Version Manager (rvm). It manages Ruby interpreter environments
and switching between them.

This package is meant for use by multiple users maintaining a shared copy of
RVM. Users added to the 'rvm' group will be able to modify all aspects
of RVM. These users will also have their default umask changed to g+w (0022) to
ensure correct permissions for the shared RVM content.

RVM is activated for all logins by default. To disable remove
/etc/profile.d/rvm.sh and source rvm from each users shell.


Goal
-----

This package were created for numerous reasons:

1. To simplify the install process.
2. To more easily install rvm during a Kickstart install.
3. To simplify the upgrade process when using package management via
   [Chef](http://opscode.com/chef/) or [Puppet](http://www.puppetlabs.com/).
4. To conform to standard filesystem paths.


Supported Distributions
-----------------------

* Centos 6.3
* CentOS 6.2
* CentOS 6.1
* CentOS 6.0
* CentOS 5.7
* CentOS 5.6
* CentOS 5.5


Support
-------

For issues with this package please contact me via the github Issue tracker or
directly at mkent@magoazul.com.


Credit
------

These packages are based off the Gentoo ebuilds within the rvm git repository.
