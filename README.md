# RaspiDNS
The dnsmasq-safesearch.conf file is a config file that tells dnsmasq to force safesearch for google, youtube, and bing searches. 
In order to use it with dnsmasq, save the file to /etc/dnsmasq-safesearch.conf, then add a line to /etc/dnsmasq.conf:

`conf-file=/etc/dnsmasq-safesearch.conf`

When dnsmasq is restarted, it will read the new conf file and enforce safesearch.
