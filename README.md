# Active Network Defense (AND) NXLog Windows Configuration
# Configure any Vista and later Windows system to forward Windows Event Log data directly to Hoplite Active Network Defense

# Microsoft SysMon Installation
* Download SysMon version 3.2, unzip the downloaded file
* Open a command prompt with Administrator privileges
* Move into the SysMon archive directory and run ‘sysmon.exe –I –h * -n'
* Follow the prompts to complete SysMon service installation

# NXLog  Installation
* The NXLog configuration file for each system should be placed in C:\Program Files (x86)\nxlog\conf\nxlog.conf
* Edit the nxlog.conf to include the IP address and/or the custom destination port on your AND appliance.
* Once NXLog has been installed and the configuration file is in place the NXLog service will need to be restarted.
