XenServer Hypervisor Reference Installer of Citrix XenServer 6.1 (Tampa)

This installer can be used to set up a server with support for XenAPI support in Openstack.

Drop the contents of the XenServer 6.1 Tampa ISO into citrix/tampa.  

Then add these two entries to XS-REPOSITORY-LIST:

    packages.openstack-supp
    packages.rrd-extras 
