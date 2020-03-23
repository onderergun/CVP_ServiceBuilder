# CVP_ServiceBuilder
Service Configlet Builder for CVP

# CVP_ServiceBuilder
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

It can be used to create a service from scratch, or just to change the description, or just to shut/no shut the interface without selecting or filling the other parameters. 



