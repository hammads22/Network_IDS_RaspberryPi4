# Network_IDS_RaspberryPi4
Since covid many people have moved to the “Work from Home” lifestyle. Many companies have downgraded to only keeping the essential employees. So, what if a company or an individual does not want to spend money on cyber security teams or on hiring firms?  What if we could build a low cost, minimal and to some extent even portable security system that could be attached to their network?  Raspberry Pi is a versatile and widely used IoT/Smart Computing device that can run many Linux distributions with its ARM-based efficient cortex. Apart from that it also supports ether and GPIO ports which can be used to connect to many appliances.   Since raspberry pi supports many Linux distributions, we can install a lightweight distribution and build up upon it.  Since the Pi also has a built-in Wi-Fi card and supports many Wi-Fi adapters with monitor mode, we can combine these to make it work like a Firewall, have DNS/DHCP capabilities and set up monitoring for intrusion detection.


To Setup the Environment you'll need:
1. Raspberry Pi 4 (4Gb version at least for a good Performance)
2. A Lan Cable
3. A SD card with Raspian image on it
4. A router with internet connectivity on it

Instructions: 
1. connect RaspberryPi with Router using the Lan Cable 
2. Power on the RaspberryPi
3. Run bash Snort_Script.sh to install and configure Snort on Raspberry Pi 4. kindly check the code for error if they occur.
4. Run bash Wlan0_setup.sh to configure hostapd and isc-dhcp-server. Make sure your wlan0 interface is not connected to the internet and is turned on. 

If all goes right, you'll have a AccessPoint coming up in the wifi as "Pi_Home".
