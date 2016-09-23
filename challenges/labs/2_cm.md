[root@ip-172-31-56-219 yum.repos.d]# ls -lrt
total 36
-rw-r--r--. 1 root root  529 Jun 12  2015 rhel-source.repo
-rw-r--r--. 1 root root  358 Jul 14  2015 redhat.repo
-rw-r--r--  1 root root 1440 Sep 23 09:43 mysql-community-source.repo
-rw-r--r--  1 root root 1414 Sep 23 09:43 mysql-community.repo
-rw-r--r--. 1 root root 6300 Sep 23 11:21 redhat-rhui.repo
-rw-r--r--  1 root root   80 Sep 23 11:21 rhui-load-balancers.conf
-rw-r--r--  1 root root  606 Sep 23 11:21 redhat-rhui-client-config.repo
-rw-r--r--  1 root root  115 Sep 23 11:36 local-cloudera.repo


cat local-cloudera.repo
[local-cm]
baseurl=file:///CM_STAGE_580/cm/5
gpgcheck=0

