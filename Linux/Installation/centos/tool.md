
# [Enable Third Party Repositories](http://www.tecmint.com/things-to-do-after-minimal-rhel-centos-7-installation/4/) --启用第三方软件库

[EPEL--Extra Packages for Enterprise Linux](http://freeloda.blog.51cto.com/2033581/1260824)

```
 yum install epel-release
 rpm -Uvh http://www.elrepo.org/elrepo-release-7.0-2.el7.elrepo.noarch.rpm
 
  下列软件都属于第三方软件
 yum install p7zip
 yum install ntfs-3g
 yum install vsftpd
```