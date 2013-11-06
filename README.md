Ceph4Win
========

Client for ceph on windows.

What is Ceph4Win?


Ceph4win is an project to write documentation and a client able to connect a windows workstation or server (windows XP SP3  and up)
to a local ceph cluster.

Most of the project implies using what already exists. We will not intend to reinvent the wheel!
We will use as most possible cygwin, and opensource/libre dev tools.


Why not using a third party gateway?

Third party gateways like samba, ftp, webdav, s3 amazone, openstack imply their own level of complexity and some gateway technologies are
not compatible for example s3 buckets can t be accessed by cephfs and data stored by cephfs is invisible by s3. Most of those 
technologies client are commercial black box with surprising behavior.

Best way to have something easy to deploy and use is to do a client for windows able to show ceph cluster as a regular 
mapped network drive.



How to participate? 

Github is public so just commit your code and someone somehow will do the merge :)

I hope we will do a great job !


