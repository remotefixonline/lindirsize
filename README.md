# lindirsize
directory size layout thing...


##To install it open a terminal window

git clone https://github.com/remotefixonline/lindirsize.git

cd lindirsize

chmod +x lindirsize

cp lindirsize /usr/bin/

##then in any directory just type lindirsize to get a size breakdown.

###-------------------------Example----------------##


[root@kvm_2 KVM]# lindirsize

289.4 GB .

110.8 GB ./MISC

33.5 GB ./templates

11.8 GB ./DNS

9.4 GB ./DHCP

6.0 GB ./SYSLOG

3.1 GB ./CMS


###-------------------------Example----------------##

##if  you get an error when you run "git clone"

##ubuntu

apt-get install git


##centos 

yum install git

##fedora

dnf install git
