# RITA (Real Intelligence Threat Analytics) in Jupyter Notebook

RITA is an open source framework for network traffic analysis sponsored by [Active Countermeasures](https://activecountermeasures.com/)

**RITA-J** is the implementation of RITA features in Jupyter Notebook. The goal is to support all types of Firewall/Proxy/DNS logs that are in CSV, TSV, or JSON format, and make it easy to analyze, hunt and detect potential C2 activity without installing additional hardware and other components to maintain.

---
The sample dataset was shared by Ali Alwashali ([@ali_alwashali](https://twitter.com/ali_alwashali)). It contains:  
- Zeek logs from malware-traffic-analysis.net PCAP files, from 2013 to 2021
- Suricata alerts triggered by the PCAP analysis

## Features
 - **Beaconing Detection**: Search for signs of beaconing behavior in and out of your network
 - **DNS Tunneling Detection** Search for signs of DNS based covert channels (TO DO)
 - **Blacklist Checking**: Query blacklists to search for suspicious domains and hosts (TO DO)
 - **More features will be added**

## Requirements
Firewall/Proxy logs that are in CSV or JSON format. If the logs are not parsed, parsing is required before analysis.  
An example for converting Fortinet logs:  
https://github.com/lucky-luk3/Infosec_Notebooks/blob/main/Forti_VPN_Logs_Analysis-Public.ipynb

## Install

Will be added

## How to Use

Will be added