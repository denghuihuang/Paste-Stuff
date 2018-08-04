Paste-Stuff
===========

Let's see what is redhat's buglist looks like?

https://bugzilla.redhat.com/buglist.cgi?component=RFEs&product=Red%20Hat%20OpenStack


http://pan.baidu.com/wap/link?uk=2214641459&shareid=1974442370&third=0


http://pan.baidu.com/s/1o6uozv8


https://repos.fedorapeople.org/repos/openstack/openstack-kilo/el7

https://azure.microsoft.com/en-us/blog/microsoft-showcases-software-defined-networking-innovation-at-sigcomm-v2/


http://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/setup-linux-container-with-lxc-on-ubuntu-16-04-14-04.html

http://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/manage-lxc-container-with-lxc-web-panel-a-web-based-interface.html

https://github.com/openstack/docs-specs/blob/master/specs/template.rst


 cookie=0x0, duration=16949.113s, table=0, n_packets=1, n_bytes=42, idle_age=16898, priority=10,arp,arp_tpa=192.168.1.5 actions=move:NXM_OF_ETH_SRC[]->NXM_OF_ETH_DST[],load:0x3->NXM_OF_ETH_SRC[],load:0x2->NXM_OF_ARP_OP[],move:NXM_NX_ARP_SHA[]->NXM_NX_ARP_THA[],move:NXM_OF_ARP_SPA[]->NXM_OF_ARP_TPA[],load:0x3->NXM_NX_ARP_SHA[],load:0xc0a80105->NXM_OF_ARP_SPA[],IN_PORT
 cookie=0x0, duration=19497.421s, table=0, n_packets=43, n_bytes=3446, idle_age=16634, priority=0 actions=NORMAL
 
 group_id=1,type=select,bucket=weight:100,actions=ct(commit,table=1,zone=1,nat(dst=192.168.1.2:8080)),bucket=weight:200,actions=ct(commit,table=1,zone=2,nat(dst=192.168.1.3:8090)),bucket=weight:300,actions=ct(commit,table=1,zone=3,nat(dst=192.168.1.4:9000))


http://linuxgazette.net/135/pfeiffer.html



 cookie=0x0, duration=1692.078s, table=0, n_packets=1566, n_bytes=287972, idle_age=20, priority=100,ip,in_port=1 actions=ct(table=1,nat)
 cookie=0x0, duration=1235.270s, table=0, n_packets=1266, n_bytes=258572, idle_age=1, priority=100,ip,in_port=2 actions=ct(table=1,nat)
 cookie=0x0, duration=1661.920s, table=0, n_packets=170, n_bytes=7140, idle_age=5, priority=0,arp actions=NORMAL
 cookie=0x0, duration=1396.845s, table=1, n_packets=1338, n_bytes=265628, idle_age=20, priority=100,ct_state=+trk,ip,in_port=1 actions=ct(commit,nat(src=192.168.1.4)),output:2
 cookie=0x0, duration=1109.393s, table=1, n_packets=1057, n_bytes=238090, idle_age=20, priority=100,ct_state=+est,ip,in_port=2 actions=output:1
 
 
 https://etherpad.openstack.org/p/newton-ovo-progress
 
 http://openstack.10931.n7.nabble.com/neutron-OVO-Status-Dashboard-td116778.html
 
 
 tc qdisc add dev qvm97f9565d-4c ingress
tc filter add dev qvm97f9565d-4c protocol ip parent ffff: prio 1 u32 match ip src 192.168.1.2 match ether src e4:11:22:33:44:50 flowid 1:16 action drop

ftp://ftp.registro.br/pub/gter/gter41/05-OpenContrail-Suporte-Legado.pdf

https://yq.aliyun.com/articles/218895


nginx分析：
https://github.com/vislee/leevis.com/issues/137

https://www.codingnow.com/temp/readinglua.pdf


http://cxd2014.github.io/2017/10/15/linux-napi/

https://blog.csdn.net/hz5034/article/details/79794478

https://www.cnblogs.com/mylinuxer/p/4272382.html

https://www.ibm.com/developerworks/cn/linux/l-napi/

https://vincent.bernat.im/en/blog/2017-vxlan-linux


https://www.cnblogs.com/mylinuxer/p/4272382.html

https://courses.engr.illinois.edu/cs423/sp2014/Lectures/LinuxDriver.pdf


https://www.central.org/dl/linuxdev/centos6/i386/

http://rpm.pbone.net/index.php3/stat/3/srodzaj/2/search/kernel-2.6.32-431.17.1.el6.src.rpm


https://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/

https://blog.csdn.net/zm_21/article/details/27208811

