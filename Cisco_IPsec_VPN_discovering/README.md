# Zabbix SNMP template for discovering and monitoring cisco IPsec tunnels


howto:

1. Import template to zabbix
2. Put MIB files to the folder /usr/share/snmp/mibs/
3. Add  host (cisco router) to zabbix  (snmp)
4. Add template to the host


Required MIB files:

CISCO-IPSEC-FLOW-MONITOR-MIB.my
SNMPv2-SMI.my
SNMPv2-CONF.my
SNMPv2-TC.my
CISCO-MEDIA-GATEWAY-MIB.my
CISCO-SMI.my

update:

Cisco_IPsec_VPN_OIDs_discovering - is clone of template Cisco_IPsec_VPN_discovering
This template discover VPN tunnels by OIDs. MIB files no needed.
All you need to do is import template and add it to the host.