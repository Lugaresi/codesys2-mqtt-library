# CoDeSys2 MQTT Library
This project initially started from backporting of http://codesys-mqtt-library.sourceforge.net/ version 3.5.0.0.  
This Client follows [MQTT Specifications v3.1.1](http://docs.oasis-open.org/mqtt/mqtt/v3.1.1/mqtt-v3.1.1.html).  
The only dependency is Standard and SysLibSockets lib.

The following MQTT features are supported:
- CONNECT (incl. randomized or defined ClientId, User/Password authentication, Last Will QoS 0, auto. reconnection) / DISCONNECT
- Keep Alive (PINGREQ / PINGRESP)
- PUBLISH QoS 0 (incl. Retain)
- SUBSCRIBE  QoS 0 (SUBACK) / UNSUBSCRIBE (UNSUBACK)
