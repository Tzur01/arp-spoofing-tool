# ARP Spoofing Tool



### Description
This Python script enables ARP spoofing attacks for network penetration testing and security assessment. It facilitates the interception and manipulation of network traffic between specified targets, providing valuable insights into network vulnerabilities and security weaknesses.

#### Features

 * Automatic IP Validation: Automatically verify the validity of target IP addresses to ensure accurate and secure spoofing.
   
 * MAC Address Retrieval: Retrieve MAC addresses associated with target IP addresses using ARP requests for seamless spoofing.
   
 * Silent Mode Option: Enable silent mode to reduce verbosity and display less output during the spoofing process.
   
 * User-friendly Interface: Utilize a straightforward command-line interface for easy configuration and execution of ARP spoofing attacks.

#### To use the tool, follow these steps:


 Make sure you have Python 3 installed on your system.
 
Install the required Python modules.

Run the script with root privileges: sudo python3 arp_spoof.py -t <target1_ip>  <target2_ip>   

Example: sudo  python3  arp_spoof.py -t 192.168.1.2   192.168.1.3  

Press Ctrl+C to stop the ARP spoofing attack and restore ARP tables.






 ##
Please note that this tool should only be used for authorized penetration testing and security assessment purposes. Unauthorized or unethical use of this tool on networks without explicit permission is illegal and irresponsible. The creator of this tool bears no responsibility for any misuse or unauthorized use, and users assume full responsibility for their actions when utilizing the tool.

