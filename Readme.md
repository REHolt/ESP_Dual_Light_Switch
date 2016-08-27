### ESP Dual LIght Switch

### Synopsis
This is a simple project to creat a wifi controlled light switch. The intent is to make it fit into a standard electrical outlet box, and for the switch to be usable in conjunction with existing 3 way switches.


## Motivation

This project was motivated by wanting to implement Home Automation using my Amazon Echo. Most of the commercial switches are expensive and don't work like I would like them to. From my perspective, for them to work correctly, they need to be vertually invisible once installed and they need to be able to work with existig wiring.

## Design descriptin
Once completed I will have two version, one with two switches and a second with only one. The design will incorporate an ESP12E chip, alnog with all the necessary power conversion (110v to +5v, and 3.3V). The circuit design will include current sensing on the common wire, so that the system will know the state of the light even if the non-wifi switch was used to turn it on.

## Pictures
The ESP12E chip makes a good solution for this effort in that it is small and easy to work with. 
![Alt text](/pictures/ESP12E.jpg?raw=true "ESP12#")
