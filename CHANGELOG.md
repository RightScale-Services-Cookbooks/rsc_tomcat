rsc_tomcat Cookbook CHANGELOG
==========================

This file is used to list changes made in each version of the rsc_tomcat cookbook.

v2.0.2
-----
 -updated maxThreads setting to exclude JasperListener for tomcat 8 and above since it had been deprecated in server.xml

v2.0.1
------
- added maxThreads as an input for tomcat 7

v2.0.0
------
- updating to Chef 12

v1.4.2
------
- adding datasource properties max_active, max_active, max_wait and port

v1.4.1
------
- change recipe to use rsc_tomcat/app_root attribute,
- set default rsc_tomcat/app_root to /home/webapps

v1.4.0
-----
- add support for chef 12

v1.3.0
------
- Rightlink 10 support, chef server support
