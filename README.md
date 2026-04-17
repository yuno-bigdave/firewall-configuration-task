# Firewall Configuration Task

## Objective
To configure and test firewall rules using UFW on Kali Linux.

## Steps Performed

I. Enabled UFW firewall  
II. Listed existing firewall rules  
III. Blocked port 23 (Telnet)  
IV. Tested blocked port using telnet  
V. Allowed SSH (port 22)  
VI. Removed block rule  

## Commands Used

sudo ufw enable  
sudo ufw status  
sudo ufw deny 23  
telnet localhost 23  
sudo ufw allow 22  
sudo ufw delete deny 23  

## Outcome
Successfully blocked and unblocked ports and understood how firewall filters network traffic.
