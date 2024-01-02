# RMM_SinkHole
A project to automate the blocking of domains and IPs for RMM and remote control tools not authorised for use on managed systems.

Anyone from any MSP are welcome to add and utilise the list - all has been obtained from publicly available sources so there should be no surprises or sensitive information within.

**Please validate any data before using in your environment.** Standard buyer beware - every network is different and we really don't want to upset yours at all. 


## Project To-Do List
* ~~Identify all other RMM or remote access tools~~
* ~~Identify sources of lists for domains / IPs used by other RMM or remote access tools~~
* ~~Create list in structured format of published IPs & domains - CSV / JSON / psobject / other(?)~~
* Create monitor to watch known pages for changes
* Create scraper to update list of sources on discovery of changes by monitor
* Create alerting following discovery of changes by monitor
* Create PowerShell script to create DNS sinkholes on Windows-based DNS servers
* Create shell scripts to create DNS sinkholes on macOS & Linux-based DNS servers
* Create API calls/apps to add to dns filtering tool global block lists
* Create API calls/apps to add blocks to firewall appliances
* Create PowerShell script to sinkhole all domains/IPs in the Windows Firewall where a domain isn't joined
* Create shell script(s) to sinkhole all domains/IPs in the macOS & Linux firewalls

**Note:** *Lineal have most of the above already. Just haven't found the bandwidth to move them into this repository as yet.*
