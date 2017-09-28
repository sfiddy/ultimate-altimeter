# i<sup>2</sup>C Precision Altimeter & The Electric Imp

![Ultimate Precision Altimeter Board](/images/Ultimate_Altimeter_Board.png)

### What kind of data is this device collecting?
The i<sup>2</sup>C Precision Altimeter (also known as the SparkFun Altitude/Pressure Sensor Breakout) is an arduino controlled sensor that provides accurate accurate Pressure/Altitude and Temperature data.
<a href="#note1" id="note1ref"><sup>1</sup></a>

### What sensors are used? 
*The SparkFun Altitude/Pressure Sensor Breakout* device employs a MEMS pressure sensor that outputs Pressure/Altitude and Temperature data. Micro-Electro-Mechanical Systems, or MEMS are tiny machines that are composed of micro-sized elements. A MEMS sensor gather informations from their surroundings while a MEMS actuator executes specific commands based off the parameters set from the data gathered by a MEMS sensor.
<a href="#note2" id="note2ref"><sup>2</sup></a>

### Where is the data being stored? Who has ownership over the data? 
![Electric Imp](/images/ElectricImp_Composite.png) 
The data collected from the Altimeter is accessed through an I<sup>2</sup>C serial interface and sent wirelessly with the help of an added component, the *Electric Imp*. Using the WiFi enabled development platform, *"Electric Imp"*, the data collected from the Altimeter is transmitted wirelessly to [ide.electricimp.com](https://ide.electricimp.com)
<a href="#note3" id="note3ref"><sup>3</sup></a>



### Is the data available to the user, and if so, in what format?



<a id="note1" href="#note1ref"><sup>1</sup></a> https://cdn.sparkfun.com/datasheets/Sensors/Pressure/MPL3115A2.pdf

<a id="note2" href="#note2ref"><sup>2</sup></a> https://www.youtube.com/watch?v=CNmk-SeM0ZI&ab_channel=ElectronDZ

<a id="note3" href="#note3ref"><sup>3</sup></a> https://learn.sparkfun.com/tutorials/arduino-wireless-communication-via-the-electric-imp
