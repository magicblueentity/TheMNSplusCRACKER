# MNSPlusTrasher
Research Tool for analyzing the security of MNS+

MNSPlusTrasher is a research and analysis tool created to demonstrate potential weaknesses in MNS+, a school network management system used by many schools in Rhineland-Palatinate, Germany.

The project aims to highlight architectural and implementation issues in legacy environments and to support security research and educational analysis.

# Releases

Compiled binaries and changelogs are available on GitHub:

https://github.com/basti564/MNSPlusTrasher/releases

Note: Versions v1.0–v1.8 are no longer distributed.

# Source Code

This project is fully open source and intended to remain open in the future.

# Current Features

The application contains several utilities that interact with components of an MNS+ environment, including diagnostic and system interaction tools.

# System Interaction

AWBSpoofer – simulates messages addressed to the AWB service

WebLog viewer (permissions required)

Open MNS+ v2 module

Open MNS+ Support portal

Simple Process Explorer

Volume Mixer

PowerShell launcher

CMD access helper (for environments where it is restricted)

User and System Information

View users who recently logged onto the current computer

Retrieve IP addresses of computers via naming scheme

Network share discovery for:

\\MNSPlusFile\

\\MNSPlusDC\

Network Share Utilities

Map and unmap standard MNS+ shares

Custom network share mapper

ShareFinder for hidden shares

Hide or show files and folders in the home share

Lock or unlock files in the home share

Desktop and UI Utilities

Wallpaper changer

Desktop shortcuts for MNS+ resources

Additional MNS+ indicator in the Windows tray

LSD Mode (translucent color overlay)

MNS+ Interaction Features

Stop screen transmission to the teacher console

RoomShareSpoofer (simulates a different room share)

Mouse button swap after login (left-handed configuration)

Experimental Functions

Lock, unlock, or shut down computers in a classroom environment via MNSInterface

Silent Execution Options

Silent mode is available for several actions:

CMD helper

PowerShell

TeacherConsole patch

Screen transmission stop

# Planned Improvements

Future work may include:

Update checking mechanism for MNSPlusTrasher

Student and computer information retrieval via Active Directory

MAC address collection utility

Extended documentation for both the project and MNS+

Automatic detection of the currently installed MNS+ version

Screenshot

Main interface:
![Main](https://user-images.githubusercontent.com/34898868/93655210-7b23d780-fa22-11ea-901b-f8afa6c62496.PNG)

