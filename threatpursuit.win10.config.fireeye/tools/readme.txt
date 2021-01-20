Welcome to ThreatPursuit VM
  __  __                __                         _ __ 
 / /_/ /  _______ ___ _/ /____  __ _________ __ __(_) /_
/ __/ _ \/ __/ -_) _ `/ __/ _ \/ // / __(_-</ // / / __/
\__/_//_/_/  \__/\_,_/\__/ .__/\_,_/_/ /___/\_,_/_/\__/ 
                        /_/                             

version 1.9 
Date 16 1 2021
=============
This distribution contains a number of tools for cyber threat intelligence and threat hunting.

Please make sure to take a snapshot after installing so you can always revert back if you have issues.

This image has the Chocolatey package manager installed, and you can continue to customize this machine with any package from the Chocolatey repository - 
https://chocolatey.org/packages

Try this:
  choco install github 
Or:
  cinst github

 To keep this distribution up to date, type this into an Administrative terminal:
  cup all


+++++++++++++
Getting Started with the VM

1. SPLUNK - To find your randomely generated password for SPLUNK navigate to %TEMP%\slunk.log and note your PASSWORD down.

2. MISP - You will need to apply the workaround mentioned in https://github.com/fireeye/ThreatPursuit-VM/issues/6 prior to configuring MISP for Docker

3. Under the Tools Directory placed on your Desktop, you will find the main categories and links to tools. These tools are mostly installed under C:\Tools\
 
For common known issues https://github.com/fireeye/ThreatPursuit-VM/wiki/Known-Issues 

For common how to's check out the Wiki https://github.com/fireeye/ThreatPursuit-VM/wiki

+++++++++++++ 


Please enjoy the VM and submit any feedback or feature requests as github 
issues here:
https://github.com/fireeye/ThreatPursuit-VM

Changelog:

1.9 - January 16th 2021
- Fixes in missing packages Microsoft Threat Hunting
- Fixes in Azure Zentinel

1.6 - November 9th 2020
- Fixed multiple packages missing from installation
- added readme.txt
- fixed THREATPURSUIT prompt in env variables
- added remove shortcuts