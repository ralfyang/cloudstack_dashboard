cloudstack_dashboard
====================

CloudStack_Dashboard_on_CLi

   * API Port enable first on Global setting of CloudStack - "Global Setting > integration.api.port > Value=8096(or whatever)"

   * nmap package requires for the ping test
     * yum install nmap -y

   * Setup the Config file as your cloudstack system
     * vi cloudstack_dashboard.conf

   * Execute the file in the same directory with config file
     * cloudstack_dashboard

   * Log file
     *  /data/logs/cloud_dashboard/cloud_work.log 

   * Sample Screen
<pre>
========================================================================================================================================================================
| No |  Hostname    |  Created      |  State    |  Template name               |  Spec.          | Use%  | Mem  | Instance   | Memo               |  IP address        |
========================================================================================================================================================================
| 1  | devel03      | 2013-11-08T14 | Running   | CentOS 6.4 - template(15G)   | Medium Instance | 0.06% | 2048 | i-5-43-VM  | Account PKG test   | 10.xx.xxx.xxx: ON  |
| 2  | devel06      | 2013-11-18T18 | Running   | CentOS 6.4 - template(15G)   | Medium Instance | 0.05% | 2048 | i-5-94-VM  | LDAP package make  | 10.xx.xxx.xxx: ON  |
| 3  | devel01      | 2013-11-20T09 | Running   | CentOS 6.4 - template(15G)   | Medium Instance | 0.05% | 2048 | i-5-121-VM |                    | 10.xx.xxx.xxx: ON  |
========================================================================================================================================================================
========================================
| Description                  |  Key  |
========================================
| Change User - ralf.yang      |  [u]  |
----------------------------------------
| Refresh the list             | Enter |
| VM Start                     |  [s]  |
| VM Stop                      |  [e]  |
| VM Create                    |  [c]  |
| VM Delete                    |  [d]  |
| VM Recovery                  |  [r]  |
| SSH Terminal                 |  [t]  |
| Memo Add / Remove            |  [m]  |
| Install default package      |  [i]  |
| Quit                         |  [q]  |
========================================
 You can type the command with the host number(ex. s2 -> start VM for No. 2 server) 
 :: Please insert a key for what you want ?

</pre>
