# Switch Check Access Sessions
A simple script to collect information about access-session on the switch.
- login to the switch
- collect all mac addresses from access-sessions
- check access-session for each mac address
- if there is FAIL in the dACL - collect info about this session:
    - interface
    - mac_address
    - ip_address
    - user_name
    - method (mab|dot1x)
    - vendor (for mab)

![image-37-1536x360](https://user-images.githubusercontent.com/39305133/81471719-aa931f80-91b8-11ea-9854-107b8824e1a3.png)

## Technologies
* Python3
* ISE
* Cisco IOS switch

## Setup
* python check_access_sessions.py <IP_ADDRESS>

* Breakdown post [here](https://dmitrygolovach.com/python-and-ise-monitor-mode/)
* How it works [youtube](https://youtu.be/qrqU43QshUY)

Example:
* python check_access_sessions.py 10.10.10.10

## Contact
* Created by Dmitry Golovach
* Web: [https://dagolovachgolovach.com](https://dmitrygolovach.com) 
* Twitter: [@dagolovach](https://twitter.com/dagolovach)
* LinkedIn: [@dmitrygolovach](https://www.linkedin.com/in/dmitrygolovach/)

- feel free to contact me!
