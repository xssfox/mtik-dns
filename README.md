Mikrotik DHCP DNS Resolver
==

This DNS resolver (based on dnslib by Paul Chakravarti) uses a mikrotik router as the backend.

Requirements
--
```
pip3 install dnslib RouterOS-api
```

Usage
--
(listens on port 54)
```
python3 -m mtikdns --port 54 --password $PASSWORD --router 172.16.0.254
```

FAQ
--
### Can I use this in production?
Yes
### Should I use this in production?
Hell no