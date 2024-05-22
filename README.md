# Template App Postfix by Zabbix Agent active

## Overview

For Zabbix version: [6.0](./6.0/), [6.4](./6.4/)

This template monitors a Postfix instance's processes and queues using the Zabbix Agent, 
[pflogsumm.pl](https://jimsun.linxnet.com/postfix_contrib.html), [logtail](https://sourceforge.net/projects/logdigest/), [postqueue](http://www.postfix.org/postqueue.1.html) and a helper script.

Monitored items are:
  - Number of different running Postfix processes
  - CPU and Memory usage of different Postfix processes
  - Postfix version
  - Number of messages in different queue's
  - Bounced, Deferred and Reject reasons
  - Mail volumes delivered/received in bytes

This template was tested on:
  - openSUSE Leap 15.4, 15.5
  - SLES 15 SP5
but should work on any Linux 

## Author

Robin Roevens