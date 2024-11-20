# IoT Car
The code for an IoT car created at school. Workload for this was equally shared between Joni and Joonas.

The code runs on Node-RED. The car has three sensors that send data to a Raspberry Pi.
This Pi then sends the data to a web server on the local network using the MQTT protocol,
from where it is retrieved and forwarded to the car's motors.

The mqtt_pi file contains the code for the Raspberry Pi in the car, while servu_mosco contains  
the code running on the web server.  
The toimiva_base_koodi file contains code for the Raspberry Pi that does not send data to the web server.  
