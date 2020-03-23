# CVP_ServiceBuilder
This configlet builder allows you to change the simple configurations related to access interfaces, like description, applying an access VLAN, add an allowed VLAN to a trunk, shut/no shut the port directly from a single GUI-like interface without manually editing the underlying configlets.

# How to Use
Tested with CVP 2019.1.2

Do not apply it to a device or container, just generate it from the builder itself. The prerequisite for the builder to work  is there needs to be a configlet with the same name as the device that was applied to the device itself. It should contain the interfaces as below between Ethernet1 and Ethernet48:

interface Ethernet1

!

interface Ethernet2

!

interface Ethernet3

!


Select the interface from the dropdown menu

Description, interface type (access or trunk), VLAN Number, Interface State can be selected/filled.
If access is selected it applies the switchport access VLAN, to the interface
If trunk is selected it adds the VLAN as an allowed VLAN.

It can be used to create a service from scratch, or just to change the description, or just to shut/no shut the interface without selecting or filling the other parameters. 



