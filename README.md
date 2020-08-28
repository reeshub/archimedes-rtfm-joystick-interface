# Acorn Archimedes RTFM Joystick Interface

**Current Status:** Gathering information.

Documenting all of the information I can get my hands on regarding the Acorn Archimedes RTFM joystick interface, a commercially-available expansion which plugs into the Econet port and provides 2x Atari-compatible 9-pin joystick ports.

The interface was compatible with all Archimedes machines and supported by [a large number of games on the system](https://forums.jaspp.org.uk/forum/viewtopic.php?f=25&t=399). Longer-term, I'd also like to document the Acorn parallel port interface so that all bases will be covered.

Some further information on the RTFM can be found here: [https://www.retro-kit.co.uk/page.cfm/content/RTFM-Joystick-interface/](https://www.retro-kit.co.uk/page.cfm/content/RTFM-Joystick-interface/)

## Clone Board By Darren Shepherd

The RTFM was a commercially available product, however [Darren Shepherd](http://dshepherd.co.uk/) has drawn up the schematics in [Autodesk Eagle](https://www.autodesk.com/products/eagle/overview) and had his own boards produced, which he has given permission to share here.

![RTFM Interface Installed In A3000](Darren%20Shepherd/Images/IMG_7692.JPG)

Pictured above: Darren's RTFM clone fitted to his Archimedes A3000. Note that he has interfaced it with the internal 9-pin port (details hopefully to follow).

For now, I'll include Darren's CAD files below. These are designed for use with [Autodesk Eagle](https://www.autodesk.com/products/eagle/overview) and are compatible with the free version.

## Bill Of Materials (Work In Progress)
- PCB
- 2.54mm Pin Header
- 2x SN74LS240N Octal Buffer / Line Driver IC
- 1x SN74LS32N Quadruple 2-Input Positive-OR Gate IC
- 2x Resistor Ladder (values TBC)
- 2x DE-9 male connector

## Downloads

- [RTFMJoy_zip,a91.dat](Darren%20Shepherd/RTFMJoy_zip,a91.dat) - Original driver software.
- [RTFMProject.rar](Darren%20Shepherd/RTFMProject.rar) - Version 1 PCB CAD package (superceded by v2 below).
    - [RTFM_2019-03-25.zip](Darren%20Shepherd/RTFMProject/RTFM_2019-03-25.zip) - Drill and Gerber files taken from the above for fabrication (superceded by v2 below).
- [RTFM2Project.rar](Darren%20Shepherd/RTFM2Project.rar) - Version 2 PCB CAD package.
    - [RTFM_201909151949.zip](Darren%20Shepherd/RTFM2Project/RTFM_201909151949.zip) - Drill and Gerber files taken from the above for fabrication.