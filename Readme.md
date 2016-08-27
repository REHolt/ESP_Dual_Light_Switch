### ESP Dual LIght Switch

### Synopsis
This is a simple project to creat a wifi controlled light switch. The intent is to make it fit into a standard electrical outlet box, and for the switch to be usable in conjunction with existing 3 way switches.


## Motivation

This project was motivated by wanting to implement Home Automation using my Amazon Echo. Most of the commercial switches are expensive and don't work like I would like them to. From my perspective, for them to work correctly, they need to be vertually invisible once installed and they need to be able to work with existig wiring.

## Design descriptin
Once completed I will have two version, one with two switches and a second with only one. The design will incorporate an ESP12E chip, alnog with all the necessary power conversion (110v to +5v, and 3.3V). The circuit design will include current sensing on the common wire, so that the system will know the state of the light even if the non-wifi switch was used to turn it on.

## Pictures
The ESP12E chip makes a good solution for this effort in that it is small and easy to work with. 
![Alt text](/pictures/ESP12E1.JPG?raw=true "ESP12#")

In order to fit properly in the Standard 2 gange Electrical outlet box the whole circuit must be <3" x 1.8" with a depth of about an 1 1/2". This leaves adequate space for wires and connections. If you have a single box you can get away with a litlle more (3" x 2" x 1.75"), but I plan to make them all a standard size to fit any box.

![Alt text](/pictures/Switch%20Cover1.JPG?raw=true "Switch Cover#")

It also eeds to fit under a cover like this, so that it will work with a standard light switch cover. the trick wil be to find a way to mount the board so that you can push the buttons. My current thought is to design a cover and have it printed on a 3D printer.

![Alt text](/pictures/Switch%20Outlet%20Box1.JPG?raw=true "Single Outlet box#")
