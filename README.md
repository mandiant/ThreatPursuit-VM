_______________________________________________________________________

          __   __                         __      
        _/  |_|  |_________  ____ _____ _/  |_    
        \   __|  |  \_  __ _/ __ \\__  \\   __\   
         |  | |   Y  |  | \\  ___/ / __ \|  |     
         |__| |___|  |__|   \___  (____  |__|     
         ______  __ _________ ________ __|___/  |
         \____ \|  |  \_  __ /  ___|  |  |  \   __\
         |  |_> |  |  /|  | \\___ \|  |  |  ||  |
         |   __/|____/ |__| /____  |____/|__||__|
         |__|                    \/

                MANDIANT THREAT INTELLIGENCE VM
                       Version 2020.1
                  threatpursuit@fireeye.com
_______________________________________________________________________

                         Created by:
                         Dan Kennedy
                  Jake Barteaux @day1player
              Blaine Stancill @MalwareMechanic
                         Nhan Huynh
          Front Line Advanced Research and Expertise

Pre-Requisites
-----------

Google Chrome Browser

Oracle Java SE 11 or Greater

Installation (Install Script)
--------------

Requirements
-----------


Recommended
-----------

* Windows 10 1903
* 120+ GB Hard Drive
* 8+ GB RAM
* 1 network adapters
* 1024mb Graphics Card Memory
* Enable Virtualization support for VM (Required for Docker)

Known Issues
-----------
Using Oracle Virtualbox as the virtualisation software running from a Windows 10 physical host, will cause issues with the Docker install. There is currently no workaround other than using VMware Player or VMware Workstation.


Instructions
-----------

Standard install

1. Create and configure a new Windows Virtual Machine
2. Ensure VM is updated completely. You may have to check for updates, reboot, and check again until no more remain
3. Take a snapshot of your machine!
4. Download and copy install.ps1 on your newly configured machine.
5. Open PowerShell as an Administrator
6. Unblock the install file by running Unblock-File .\install.ps1
7. Enable script execution by running Set-ExecutionPolicy Unrestricted -f
8. Finally, execute the installer script as follows:
.\install.ps1
You can also pass your password as an argument: .\install.ps1 -password <password>
The script will set up the Boxstarter environment and proceed to download and install the ThreatPursuit VM environment. You will be prompted for the administrator password in order to automate host restarts during installation. If you do not have a password set, hitting enter when prompted will also work.


Installed Tools
-----------

### Development, Analytics and Machine Learning
- Shogun
- Tensorflow
- Pytorch 
- Rstudio
- RTools
- Darwin
- Keras
- Apache Spark
- Elasticsearch
- Kibana
- Apache Zeppelin
- Jupyter Notebook
- MITRE Caret
- Python (x64)

### Visualisation

- Constellation
- Neo4J
- CMAP 
 
### Triage, Modelling & Hunting

- MISP
- OpenCTI
- Maltego
- Splunk 
- Microsoft MSTIC Jupyter and Python Security Tools 
- MITRE ATT&CK Navigator
- Cortex Analyzer
- Greynoise API and GNQL 
- threatcrowd API
- threatcmd
- ViperMonkey
- Threat Hunters Playbook
- MITRE TRAM
- SIGMA
- YETI
- Azure Zentinel 
- AMITT Framework

### Adversarial Emulation

- MITRE Calderra
- Red Canary ATOMIC Red Team
- Mordor Re-play Adversarial Techniques
- MITRE Caltack Plugin
- APTSimulator
- FlightSim


### Information Gathering

- Maltego
- nmap
- intelmq 
- dnsrecon
- orbit
- FOCA

### Utilities and Links

- CyberChef
- KeepPass
- FLOSS
- peview
- VLC
- AutoIt3
- Chrome
- OpenVPN
- Sublime
- Notepad++
- Docker Desktop
- HxD
- Sysinternals
- Putty
