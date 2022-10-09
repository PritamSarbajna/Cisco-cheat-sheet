|COMMAND|PURPOSE|
|:---:|:---:|
|`ip route network-number network-mask {ip-address \| interface}`|Sets a static route in the IP routing table| | |
|`router rip`|Enables a Routing Information Protocol (RIP) routing process, which places you in router configuration mode| | |
|`network ip-address`|In router configuration mode, associates a network with a RIP routing process| | |
|`version 2`|In router configuration mode, disables automatic summarization| | |
|`no auto-summary`|In router configuration mode, disables automatic summarization| | |
|`passive-interface interface`|In router configuration mode, sets only that interface to passive RIP mode. In passive RIP mode, RIP routing updates are accepted by, but not sent out of, the specified interface| | |
|`show ip rip database`|Displays the contents of the RIP routing database| | |
|`ip nat [inside \| outside]`|An interface configuration mode command to designate that traffic originating from or destined for the interface is subject to NAT| | |
|`ip nat inside source {list{access-list-number \| access-list-name}} interface type number[overload]`|A configuration mode command to establish dynamic source translation. Use of the “list” keyword enables you to use an ACL to identify the traffic that will be subject to NAT. The “overload” option enables the router to use one global address for many local addresses.| | |
|`ip nat inside source static local-ip global-ip`|A configuration mode command to establish a static translation between an inside local address and an inside global address| | |
|`vlan`|Creates a VLAN and enters VLAN configuration mode for further definitions| | |
|`switchport access vlan`|Sets the VLAN that the interface belongs to| | |
|`switchport trunk encapsulation dot1q`|Specifies 802.1Q encapsulation on the trunk link| | |
|`switchport access`|Assigns this port to a VLAN| | |
|`vlan vlan-id [name vlan-name]`|Configures a specific VLAN name (1 to 32 characters)| | |
|`switchport mode { access \| trunk }` |Configures the VLAN membership mode of a port. The access port is set to access unconditionally and operates as a non-trunking, single VLAN interface that sends and receives non-encapsulated (non-tagged) frames. An access port can be assigned to only one VLAN. The trunk port sends and receives encapsulated (tagged) frames that identify the VLAN of origination. A trunk is a point-to-point link between two switches or between a switch and a router| | |
|`switchport trunk`|Sets the trunk characteristics when the interface is in trunking mode. In this mode, the switch supports simultaneous tagged and untagged traffic on a port| | |
|`encapsulation dot1q vlan-id`|A configuration mode command that defines the matching criteria to map 802.1Q frames ingress on an interface to the appropriate service instance| | |
