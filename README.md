# lern-webmin
lern-webmin


## install fedora 34

````
cat /etc/os-release

wget http://www.webmin.com/download/rpm/webmin-current.rpm

dnf -y install perl perl-Net-SSLeay openssl perl-IO-Tty perl-Encode-Detect

rpm -U webmin-current.rpm
````


### The current Webmin distribution is available in various package formats for download from:

````
Unix tar/gzip format
https://prdownloads.sourceforge.net/webadmin/webmin-2.000.tar.gz 15.1 MB

RPM suitable for Redhat, Fedora, CentOS, SuSE or Mandrake Linux
https://prdownloads.sourceforge.net/webadmin/webmin-2.000-1.noarch.rpm 16.3 MB

Debian package suitable for Debian, Ubuntu or other derived Linux
https://prdownloads.sourceforge.net/webadmin/webmin_2.000_all.deb 14.8 MB

Source RPM suitable for Redhat, Fedora, CentOS, SuSE or Mandrake Linux
https://prdownloads.sourceforge.net/webadmin/webmin-2.000-1.src.rpm 15.1 MB

Solaris package format
https://prdownloads.sourceforge.net/webadmin/webmin-2.000.pkg.gz 14.8 MB

ZIP format suitable for Windows
https://prdownloads.sourceforge.net/webadmin/webmin-2.000.zip 19.3 MB

Minimal version of Webmin, Unix tar/gzip format
https://prdownloads.sourceforge.net/webadmin/webmin-2.000-minimal.tar.gz 1.9 MB
````
