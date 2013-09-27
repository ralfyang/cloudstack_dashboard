cloudstack_dashboard
====================

CloudStack_Dashboard_on_CLi

   * Config first for your cloudstack system
     * vi cloudstack_dashboard.conf

   * Execute the file in the same directory with config file
     * cloudstack_dashboard

   * Log file
     *  /data/logs/cloud_dashboard/cloud_work.log 

   * Sample Screen
<pre>
===================================================================================================================================================
| No |  Hostname    |  Created      |  State    |  Template name               |  Spec.          | Use%  | Mem  | Instance   |  IP address        |
===================================================================================================================================================
| 1  | devel17      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 17.0% | 1024 | i-3-93-VM  | 10.xxx.xxx.240: ON  |
| 2  | devel16      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-92-VM  | 10.xxx.xxx.239: ON  |
| 3  | devel15      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-91-VM  | 10.xxx.xxx.238: ON  |
| 4  | devel14      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 15.0% | 1024 | i-3-90-VM  | 10.xxx.xxx.237: ON  |
| 5  | devel13      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-89-VM  | 10.xxx.xxx.236: ON  |
| 6  | devel12      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-88-VM  | 10.xxx.xxx.235: ON  |
| 7  | devel11      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 14.0% | 1024 | i-3-87-VM  | 10.xxx.xxx.234: ON  |
| 8  | devel10      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-86-VM  | 10.xxx.xxx.233: ON  |
| 9  | devel09      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-85-VM  | 10.xxx.xxx.232: ON  |
| 10 | devel08      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-84-VM  | 10.xxx.xxx.231: ON  |
| 11 | devel07      | 2013-09-27T10 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-77-VM  | 10.xxx.xxx.230: ON  |
| 12 | devel06      | 2013-09-27T10 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 15.0% | 1024 | i-3-76-VM  | 10.xxx.xxx.229: ON  |
| 13 | devel05      | 2013-09-27T10 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.3% | 1024 | i-3-75-VM  | 10.xxx.xxx.228: ON  |
| 14 | devel04      | 2013-09-27T10 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-74-VM  | 10.xxx.xxx.227: ON  |
| 15 | devel03      | 2013-09-27T10 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 14.0% | 1024 | i-3-73-VM  | 10.xxx.xxx.226: ON  |
| 16 | devel02      | 2013-09-27T10 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-72-VM  | 10.xxx.xxx.225: ON  |
| 17 | devel01      | 2013-09-27T10 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.1% | 1024 | i-3-71-VM  | 10.xxx.xxx.224: ON  |
| 18 | devel20      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 15.0% | 1024 | i-3-96-VM  | 10.xxx.xxx.243: ON  |
| 19 | devel19      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 16.0% | 1024 | i-3-95-VM  | 10.xxx.xxx.242: ON  |
| 20 | devel18      | 2013-09-27T15 | Running   | CentOS 6.4 - template(20G)   | Medium Instance | 17.3% | 1024 | i-3-94-VM  | 10.xxx.xxx.241: ON  |
===================================================================================================================================================
========================================
| Description                  |  Key  |
========================================
| Refresh the list             | Enter |
| VM Start                     |  [s]  |
| VM Stop                      |  [e]  |
| VM Create                    |  [c]  |
| VM Delete                    |  [d]  |
| VM Recovery                  |  [r]  |
| eXit                         |  [x]  |
========================================
 You can type the command with the host number(ex. s2 -> start VM for No. 2 server) 
 :: Please insert a key for what you want ? 
</pre>
