 VLAN + Router-on-a-Stick + DHCP Lab
    Description
 This lab shows how to:
 - Create VLANs on switches
 - Connect VLANs using Router-on-a-Stick method
 - Configure DHCP on the router to give IP addresses

   Devices Used
 - 1 Router
 - 1 Switches
 - 4 PCs

   Configurations
 - VLAN 10 (Sales), VLAN 20 (HR)
 - Router sub-interfaces: g0/0.10 and g0/0.20
 - DHCP pool for each VLAN
 - Trunk port between switch and router

   Test
 - PCs got IP from DHCP
 - Successful ping between VLANs

   Files
  vlan_lab.pkt