# i<sup>2</sup>C Precision Altimeter & The Electric Imp

![Ultimate Precision Altimeter Board](/images/Ultimate_Altimeter_Board.png)

### What kind of data is this device collecting?
The i<sup>2</sup>C Precision Altimeter (also known as the SparkFun Altitude/Pressure Sensor Breakout) is an arduino controlled sensor that provides accurate accurate Pressure/Altitude and Temperature data.
<a href="#note1" id="note1ref"><sup>1</sup></a>

### What sensors are used? 
*The SparkFun Altitude/Pressure Sensor Breakout* device employs a MEMS pressure sensor that outputs Pressure/Altitude and Temperature data. Micro-Electro-Mechanical Systems, or MEMS are tiny machines that are composed of micro-sized elements. A MEMS sensor gather informations from their surroundings while a MEMS actuator executes specific commands based off the parameters set from the data gathered by a MEMS sensor.
<a href="#note2" id="note2ref"><sup>2</sup></a>

### Where is the data being stored?
![Electric Imp](/images/ElectricImp_Composite.png) 
Using the WiFi enabled development platform, *"Electric Imp"*, the data collected from the Altimeter is transmitted wirelessly and stored in ...


The unit can be programmed to periodically capture Altitude/Pressure and Temperature data. Up to 32 data acquisitions can
be stored in the internal FIFO. The interval between acquisitions is programmable from 1 second to 9 hours. The registers embedded inside the device are accessed through an I2C serial interface.

### Who has ownership over the data? 

### Is the data available to the user, and if so, in what format?

[2]: http://www.instructables.com/id/The-Ultimate-Altimeter-A-compact-Arduino-altimeter/

<a id="note1" href="#note1ref"><sup>1</sup></a> https://cdn.sparkfun.com/datasheets/Sensors/Pressure/MPL3115A2.pdf

<a id="note2" href="#note2ref"><sup>2</sup></a> https://www.youtube.com/watch?v=CNmk-SeM0ZI&ab_channel=ElectronDZ
