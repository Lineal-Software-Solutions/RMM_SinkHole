# RMM_SinkHole
A project to automate the blocking of domains and IPs for RMM and remote control tools not authorised by Lineal for our clients.

## Project To-Do List
* Identify all other RMM or remote access tools
* Identify sources of lists for domains / IPs used by other RMM or remote access tools
* Create list in structured format of published IPs & domains
* Create monitor to watch known pages for changes
* Create scraper to update list of sources on discovery of changes by monitor
* Create alerting for internal team following discovery of changes by monitor
* Create PowerShell script to create DNS sinkholes on Windows-based DNS servers
* Create shell scripts to create DNS sinkholes on macOS & Linux-based DNS servers
* Create API calls/apps to add to DNS Filter global block lists
* Create API calls/apps to add blocks to all Meraki MX appliances
* Create PowerShell script to sinkhole all domains/IPs in the Windows Firewall where a domain isn't joined
* Create shell script(s) to sinkhole all domains/IPs in the macOS & Linux firewalls
