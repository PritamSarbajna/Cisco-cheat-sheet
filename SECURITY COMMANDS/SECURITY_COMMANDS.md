|COMMAND|PURPOSE|
|:---:|:---:|
|`password pass-value`|Lists the password that is required if the login command (with no other parameters) is configured| | |
|`username name password pass-value`|A global command that defines one of possibly multiple user names and associated passwords used for user authentication. It is used when the login local line configuration command has been used| | |
|`enable password pass-value`|A configuration mode command that defines the password required when using the enable command| | |
|`enable secret pass-value`|A configuration mode command that sets this Cisco device password that is required for any user to enter enable mode| | |
|`service password-encryption`|A configuration mode command that directs the Cisco IOS software to encrypt the passwords, CHAP secrets, and similar data saved in its configuration file| | |
|`ip domain-name name`|Configures a DNS domain name| | |
|`crypto key generate rsa`|A configuration mode command that creates and stores (in a hidden location in flash memory) the keys that are required by SSH| | |
|`transport input {telnet \| ssh}`|Used in vty line configuration mode, defines whether Telnet or SSH access is allowed into this switch. Both values can be specified in a single command to allow both Telnet and SSH access (default settings)| | |
|`access-list access-list-number {deny \| permit} source [source-wildcard] [log]`|A configuration mode command that defines a standard IP access list| | |
|`access-class`|Restricts incoming and outgoing connections between a particular vty (into a basic Cisco device) and the addresses in an access list| | |
|`ip access-list {standard \| extended} {access-list-name \| access-list-number}`|A configuration mode command that defines an IP access list by name or number| | |
|`permit source [source-wildcard]`|Used in ACL configuration mode to set conditions to allow a packet to pass a named IP ACL. To remove a permit condition from an ACL, use the “no” form of this command| | |
|`deny source [source-wildcard]`|Used in ACL configuration mode to set conditions in a named IP ACL that will deny packets. To remove a deny condition from an ACL, use the “no” form of this command| | |
|`ntp peer <ip-address>`|Used in global configuration mode to configure the software clock to synchronize a peer or to be synchronized by a peer| | |
|`switchport port-security`|Used in interface configuration mode to enable port security on the interface| | |
|`switchport port-security maximum maximum`|Used in interface configuration mode to set the maximum number of secure MAC addresses on the port| | |
|`switchport port-security mac-address {mac-addr \| {sticky [mac-addr]}}`|Used in interface configuration mode to add a MAC address to the list of secure MAC addresses. The “sticky” option configures the MAC addresses as sticky on the interface| | |
|`switchport port-security violation {shutdown \| restrict protect}`|Used in interface configuration mode to set the action to be taken when a security violation is detected| | |
|`show port security [interface interface-id]`|Displays information about security options configured on the interface| | |
