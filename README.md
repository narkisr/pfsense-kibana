# Intro

ELK-5 setup for Pfsense, including:

Logstash:

 * Syslog input and elastic output with filtering.
 * Grok rules for analysing Pfsense logs blocked ips and geo info
 * snort filter beats input and elastic output with filtering.
 
Beats:
  * filebeat.yml for steaming snort log files into logstash.

# Sources

 * Setting up (beats)[https://rareintel.com/2016/07/10/installing-logstash-filebeat-directly-pfsense-2-3/] in pfsense and logstash configuration.

 * Processing Pfsense [syslog]( http://secretwafflelabs.com/2015/11/06/pfsense-elk/) using Logstash and Kibana.

