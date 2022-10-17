Every information that already are in my THM/Networking repository will not be displayed here.

# DNS Type 

A : get the IPV4 adress

AAAA : get the IPV6 adress

PTR : opposite of A or AAAA (you give it an IP and it will display the DNS)

MX : mail server name

# DNS problem 

- Flood : shuts down the DNS access. Contacting the DNS will not be possible anymore.

- Cache Poisoning : change the information in the cache to make it send critical infirmations. A pirate could, when you try accessing Facebook.com, return the IP adress of the pirate's site and create a very big phishing attack

# Protection

Do not allow port 53 connections if you don't need it.

Securise your DNS by using DNSSEC
