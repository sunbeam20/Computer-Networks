# Computer-Networks
Network Design



A network design for Sarawak Borneo Tourism Board with a total number of
185 employees with larger IP address block 162.30.14/16 will be assigned as its
major IP address


The Main office Kuching site will connect to other 4 branches office Bintulu,
Miri, Sibu and Limbang through point to point leased line made of fiber optics.
The main offices there are the Finance department, Marketing department,
communications division, Human resource department, administration and
product management department and the Kuching office are handling IP
addresses up to 56 hosts. Also Assigning IP addresses to host in different
VLANs in the network.
The Main Office will house the server room with DNS, DHCP, Mail and web
Server connecting with an encrypted router


The Event Organization Department and Visitors information centres will be
Situated in Bintulu, Miri, Sibu and Limbang. The four branches are responsible
for these two departments. The network will have the capacity of providing
234 hosts.


Network Protocol Used in this Network Design

Routing

OSPF- Router ospf 1

Dynamic routes are configured on each branches office and in main office, to
route the traffic from inside network to another branch network.


DNS(Domain name system)

DNS is configured in DNS server, which is in the server room in kuching office.
All the hosts in this network are assumed to be connected to domain.
162.30.15.85 and 162.30.15.84 will be assigned to Web Server.


(DHCP, HTTP)

DHCP is configured in the DHCP server, which is in the server room in the
Kuching office 162.30.15.82 will be assigned to this server . Each of the hosts’
IP addresses in this network system will be Allocated dynamically.


(SMTP- simple mail transfer protocol)

Email, FTP is configured in the FTP server, which is in the server room in the
Kuching office 162.30.15.83 will be assigned to this server. Sarawak Borneo
Tourism Board has their own email server. This could provide email addresses
as much as needed and any Employee can send and receive email through this
network system. For instance Email: user1@mail.abc.com.my


VLAN

Vlan 10 is used to group the Board Unit.


Network Security

Every router has been configured with access control.
for example Username: Limbang , Password:1234.
