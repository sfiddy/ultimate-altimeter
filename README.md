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
* FIFO - The unit periodically captures data in set intervals determined by the programmer. 

#### Possible Wireless transmission

![Electric Imp](/images/ElectricImp_Composite.png) 
The data collected from the Altimeter is accessed through an I<sup>2</sup>C serial interface and can be sent wirelessly with the help of an added component, the *Electric Imp*. Using this WiFi enabled development platform (*"Electric Imp"*), the data collected from the Altimeter will be transmitted wirelessly to [ide.electricimp.com](https://ide.electricimp.com)
<a href="#note3" id="note3ref"><sup>3</sup></a>


### Who has ownership over the data? 
The user retains ownership of their own data and related intellectual property rights. However, Electric Imp reserves the right to reproduce, use, disclose, distribute and other exploit "unsolicited information". 

As stated in Electric Imp's private policy:
<a href="#note4" id="note4ref"><sup>4</sup></a>

> ***Electric Imp Intellectual Property** Electric Imp owns all right, title and interest in and the impOS™, Software, Services, the Documentation, all other parts of imp Technology, and all related Intellectual Property Rights. No rights or licenses are granted by Electric Imp except as expressly set forth in this Agreement. All other rights are expressly reserved by Electric Imp.*/

> ***Customer Intellectual Property** You own all right, title and interest in and to Customer Data, the Firmware and Agents created by you, and all related Intellectual Property Rights.*

### Is the data available to the user, and if so, in what format? 
![Electric Imp Data path](/images/ElectricImp_DataPath.png)
The sensor outputs from the Altimeter are converted from an analog signal to a digital signal. If transmitting the data wirelessly using the *Electric Imp*, the data is first sent either to the BlinkUp mobile app, or the Imp Cloud. The data is then transmitted through the impCloud server. A designated parking website can poll an http request to the redboard via the imCloud server. For the purposes of my concept, you only need to store the altitude value stored from the previous reading. 
 

### How far can you trace the physical development of the device, its materials and manufacture?
![Data path](/images/DataPath.png)

---

### Task: Replicate and Replace, Critique

![Fritzing Prototype](/images/Prototype.png)

The prototype above retains the intended functionality of the IoT device but incorporates an untraditional mode of data transmission. My prototype attaches the Electric Imp Data path that acts as a mediator between the device and internet control resources. Adding this wireless functionality allows the user to retain ownership of the data, and any software developed by the user. This allows the user to retain more ownership as Nxp has "exclusive rights to goods designed and manafactured for the unique needs of the Buyer, to Buyer's specfications or requirements."
<a href="#note4" id="note4ref"><sup>4</sup></a>

The best way to present this work to the public is by emphasizing the relationship between these 2 devices. Publishing this material in a github account, or webpage will reach the intended audience. This IoT relationship is targeting to "makers".


---

<a id="note1" href="#note1ref"><sup>1</sup></a> https://cdn.sparkfun.com/datasheets/Sensors/Pressure/MPL3115A2.pdf

<a id="note2" href="#note2ref"><sup>2</sup></a> https://www.youtube.com/watch?v=CNmk-SeM0ZI&ab_channel=ElectronDZ

<a id="note3" href="#note3ref"><sup>3</sup></a> https://learn.sparkfun.com/tutorials/arduino-wireless-communication-via-the-electric-imp
<a id="note4" href="#note4ref"><sup>4</sup></a>  https://www.nxp.com/about/about-nxp/about-nxp/our-terms-and-conditions-of-commercial-sale:TERMSCONDITIONSSALE

<a id="note5" href="#note5ref"><sup>5</sup></a> https://electricimp.com/terms/

<a id="note6" href="#not6ref"><sup>5</sup></a> http://blog.electricimp.com/post/162934055170/electric-imp-announces-secure-high-performance


