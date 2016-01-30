# TA_sudo
sudo technology add-on (TA) for Splunk

This app provides field extractions and normalisation to the Common Information Model.

Install this app on both indexers and search heads.

N.B. This app will automatically change the sourcetype of sudo events with the sourcetype of "syslog" or "linux_secure" into the "sudo" sourcetype.
