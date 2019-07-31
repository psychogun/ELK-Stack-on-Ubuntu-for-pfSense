# How to install the ELK Stack on Ubuntu for pfSense
So, on a whim I googled syslog + pfsense, and I saw some images of some nice dashboards (Kibana) for the firewall logs from pfSense. The tutorials I found did not tell me exactly how this all works, particularly how Elasticsearch, Logstash and Kibana work together. 

These instructions will tell you what I have learned and how I installed the Elastic Stack (Elasticsearch, Logstash, Kibana, Beats and SHIELD) on Ubuntu with encrypted communication, so that I could have a nice visualization of my pfSense firewall logs with syslogs and netflow.

## Prerequisites
* Clean Ubuntu 18.04 LTS 
* Java 8
* Elasticsearch 7.2 
* Logstash 7.2
* Kibana 7.2
* pfSense 2.4.4

# Instructions
For installation instructions, go to https://psychogun.github.io/docs/linux/ELK-stack-on-Ubuntu-with-pfSense/

## Acknowledgments
* http://pfelk.3ilson.com
* https://arnaudloos.com/2019/enable-x-pack-security/
* https://extelligenceblog.it/2017/10/18/elasticstack-elk-and-pfsense-firewall-ip-traffic-statistics-with-netflow/
* https://help.ubuntu.com/lts/serverguide/certificates-and-security.html
* https://github.com/solvaholic/solvaholic.github.io/wiki/Netflow-with-pfSense-and-ELK
* https://www.elastic.co/elk-stack
* https://github.com/patrickjennings/logstash-pfsense
* https://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-ubuntu-18-04-ubuntu-16-04.html
* https://logz.io/blog/elk-stack-raspberry-pi/
* https://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-ubuntu-18-04-ubuntu-16-04.html
* http://extelligenceblog.it/2017/07/11/elastic-stack-suricata-idps-and-pfsense-firewall-part-1/
* https://forum.netgate.com/topic/107735/elk-pfsense-2-3-working/2
* https://vitux.com/how-to-setup-java_home-path-in-ubuntu/
* http://secretwafflelabs.com/2015/11/06/pfsense-elk/
* https://www.elastic.co/guide/en/logstash/current/plugins-filters-grok.html#plugins-filters-grok-patterns_dir