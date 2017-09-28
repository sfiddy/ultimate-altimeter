# i<sup>2</sup>C Precision Altimeter & The Electric Imp

![Ultimate Precision Altimeter Board](/images/Ultimate_Altimeter_Board.png)

### What kind of data is this device collecting?
The i<sup>2</sup>C Precision Altimeter (also known as the SparkFun Altitude/Pressure Sensor Breakout) is an arduino controlled sensor that provides accurate accurate Pressure/Altitude and Temperature data.
<a href="#note1" id="note1ref"><sup>1</sup></a>

### What sensors are used? 
*The SparkFun Altitude/Pressure Sensor Breakout* device employs a MEMS pressure sensor that outputs Pressure/Altitude and Temperature data. Micro-Electro-Mechanical Systems, or MEMS are tiny machines that are composed of micro-sized elements. A MEMS sensor gather informations from their surroundings while a MEMS actuator executes specific commands based off the parameters set from the data gathered by a MEMS sensor.
<a href="#note2" id="note2ref"><sup>2</sup></a>

### Where is the data being stored? 

The data is stored within the registers of the Altimeter. There are 3 storage modes available:
* Polling - 
* Interupt - New data is overrides any data in the register when an event determined by the programmer occurs. 
* FIFO - the unit periodically captures data in set intervals determined by the programmer. 

#### Possible Wireless transmission

![Electric Imp](/images/ElectricImp_Composite.png) 
The data collected from the Altimeter is accessed through an I<sup>2</sup>C serial interface and can be sent wirelessly with the help of an added component, the *Electric Imp*. Using this WiFi enabled development platform (*"Electric Imp"*), the data collected from the Altimeter will be transmitted wirelessly to [ide.electricimp.com](https://ide.electricimp.com)
<a href="#note3" id="note3ref"><sup>3</sup></a>


### Who has ownership over the data? 
Electric Imp reserves the right to reproduce, use, disclose, distribute and other exploit "unsolicited information". 

As stated in Electric Imp's private policy:

> *This Privacy Policy also does not apply to any unsolicited information you provide to Electric Imp through the Service, the Site, via email, support links, or any other means.This includes, but is not limited to, information posted on any public areas of the Service or the Site, such as forums or wikis, any ideas for new products or modifications to existing products, and other unsolicited submissions (collectively, “Unsolicited Information”). All Unsolicited Information shall be deemed to be non-confidential and Electric Imp shall be free to reproduce, use, disclose, distribute, and otherwise exploit such Unsolicited Information without limitation or attribution. Please do not submit or share any Personal Information via the forums or wikis (or other public locations) that you do not wish others to know, e.g., credit card numbers, email addresses, phone numbers, mailing addresses, etc.*
<a href="#note4" id="note4ref"><sup>4</sup></a>

### Is the data available to the user, and if so, in what format?

### How far can you trace the path of the data? 
### How far can you trace the physical development of the device, its materials and manufacture?


<a id="note1" href="#note1ref"><sup>1</sup></a> https://cdn.sparkfun.com/datasheets/Sensors/Pressure/MPL3115A2.pdf

<a id="note2" href="#note2ref"><sup>2</sup></a> https://www.youtube.com/watch?v=CNmk-SeM0ZI&ab_channel=ElectronDZ

<a id="note3" href="#note3ref"><sup>3</sup></a> https://learn.sparkfun.com/tutorials/arduino-wireless-communication-via-the-electric-imp

<a id="note4" href="#not43ref"><sup>4</sup></a> https://electricimp.com/privacy/


[2]: http://www.instructables.com/id/The-Ultimate-Altimeter-A-compact-Arduino-altimeter/
