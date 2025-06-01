# Task-1
# Screenshots are attached inside file
This task involved scanning a local IP range using `nmap` and analyzing TCP SYN packets with Wireshark to identify open/filtered ports and potential security risks.


## Steps Performed
1. Identified local IP range (e.g., 192.168.1.0/24)
2. Ran a TCP SYN scan:  
   
   nmap -sS 192.168.1.0/24

## Captured packets using Wireshark with the filter
tcp.flags.syn == 1 and tcp.flags.ack == 0

