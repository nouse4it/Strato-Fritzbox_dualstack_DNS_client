[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

# strato-fritzbox_dualstack_dns_client
As Strato doesn´t support Dual Stack DynDNS with integrated DynDNS Client on FritzBox at the moment, you can use this script to read both, your IPv4 and IPv6 WAN Address
from your Fritzbox and push them via DynDNS to Strato.

Author: nouse4it <github@schlueter-online.net>

update_dyn_dns.py
Illustrate the following conecepts:
- Update IPv4 and IPv6 Address of Fritzbox per Script and Cronjob

## Use Case Description

The script reads you external IP Address to publish them to Strato and to DNS.
Use this script with a cronjob to automatically update your IP Adresses

## Installation
Pleae use the following python modules:

    fritzconnection >= 1.4.2
    requests
    
For more informations see ---> https://fritzconnection.readthedocs.io/en/1.4.2/
