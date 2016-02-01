# TA-tshark_dns
CIM compliant Tshark TA for passive DNS


Captures data in the following format created by:

/usr/bin/tshark -p -T fields -e ip.addr -e dns.id -e dns.qry.name  -E separator='; ' -n -i eth0


192.168.254.128,192.168.254.2;4650;ap.no;
192.168.254.2,192.168.254.128;4650;ap.no;152.90.247.44
