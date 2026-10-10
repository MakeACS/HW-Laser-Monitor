# Laser Monitor

The laser monitor is a system that is intended to interface with MakeACS-controlled laser cutters that use a DB9 control interface (Epilog, etc.) for their fume extractor. The Laser Monitor serves as a visual reminder to the end-user of the state of safety systems, and can stop use of the laser cutter if a safety system is not set up properly. Beyond giving user feedback regarding filter/air system states, the Laser Monitor can also track real usage hours for maintenance, and provides control channels to allow things like compressed air to be turned off when not in use. 

This project is an improvement over the previous Laser Monitor, which can be found [here](https://github.com/rit-construct-makerspace/laser-monitor). 

Improvements over previous version:
* Fail-on fume extractor controls; if the Laser Monitor loses power it turns on the fume extractor.
* Extractor power monitoring; monitors for if the fume extractor is powered on.
* Air control; terminals to attach an air solenoid, to turn off air assist when machine is not in use.
* Backup emergency light; if the laser is powered on but not the Laser Monitor, an indicator emergency light will flash. 
* MakeACS 3.0 interface; implements MakeACS 3.0 communication and power interface, for communication with newer hardware.

## License
This project is licensed under the CERN-OHL-S 2.0 License. See LIECENSE.txt for more information.
