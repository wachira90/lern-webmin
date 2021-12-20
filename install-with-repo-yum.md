# Using the Webmin YUM repository

## add repo 

### nano /etc/yum.repos.d/webmin.repo

````
[Webmin]
name=Webmin Distribution Neutral
#baseurl=https://download.webmin.com/download/yum
mirrorlist=https://download.webmin.com/download/yum/mirrorlist
enabled=1
gpgkey=https://download.webmin.com/jcameron-key.asc
gpgcheck=1
````

## import key
````
wget https://download.webmin.com/jcameron-key.asc
rpm --import jcameron-key.asc
````

## install
````
yum install perl
yum install webmin
````
