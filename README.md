RFC3442 classless static route support for IPCONFIG/KLIBC 1.5.25 

KLIBC ipconfig patch for klibc 1.5.25
to apply this patch you need to add it to the debian package source and then rebuild it.
You could do something like this:
apt-get source klibc-1.5.25
dpkg-buildpackage
