# Example of using the command pattern with a serial port

## Disclaimer
This is a personal guide not a peer reviewed journal or a sponsored publication. We make
no representations as to accuracy, completeness, correctness, suitability, or validity of any
information and will not be liable for any errors, omissions, or delays in this information or any
losses injuries, or damages arising from its display or use. All information is provided on an as
is basis. It is the reader’s responsibility to verify their own facts.

The views and opinions expressed in this guide are those of the authors and do not
necessarily reflect the official policy or position of any other agency, organization, employer or
company. Assumptions made in the analysis are not reflective of the position of any entity
other than the author(s) and, since we are critically thinking human beings, these views are
always subject to change, revision, and rethinking at any time. Please do not hold us to them
in perpetuity.

## Overview 
It is sometimes a requirement to interface with equipment via a serial port.  Handling RS232 (or any other text based commands) can become a problem to implement if the equipment has a high number of commands, responses which are custom to the sent command, or multiple versions of a command set. 

This can all be simplified by implementing the command pattern in OOP which is shown in this project

## TwinCAT
This project uses TcXaeShell 3.1.4024.15

## Getting started
This is not a guide for TcXaeShell, please visit http://beckhoff.com/ for further guides
* This is for demo only and will need further hardware in order to run the code. 

