Lizardfs ebuild
================

1- RTFM

http://www.funtoo.org/Local_Overlay

2- Get this overlay:

~~~~
# mkdir -p /var/overlay ; cd /var/overlay
# git clone https://github.com/coffnix/lizardfs-funtoo-overlay.git
~~~~


3- Configure /etc/make.conf:

~~~~
# echo 'PORTDIR_OVERLAY="/var/overlay/lizardfs-funtoo-overlay"' >> /etc/make.conf
~~~~

4- Update your database:

~~~
# emerge app-portage/eix
# eix-update
~~~

5- Compile Lizarfs:

~~~
# emerge sys-cluster/lizardfs
~~~
