# TA_sudo
sudo technology add-on (TA) for Splunk

This app provides field extractions and normalisation to the Common Information Model.

Install this app on heavy forwarders, indexers and search heads.

N.B. This app will automatically change the sourcetype of sudo events with the sourcetype of "syslog" or "linux_secure" into the "sudo" sourcetype, however where possible it's recommended to configure sudo to log to its own log file (i.e. /var/log/sudo - please see sudo man page for instructions) and ingest that file with an inputs.conf monitor stanza, specifying "sudo" as the sourcetype.

Further documentation is provided in the wiki here: https://github.com/doksu/TA_sudo/wiki
