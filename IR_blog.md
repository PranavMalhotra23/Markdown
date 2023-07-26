# ***Learn sensing with IR***
**Do you wish to explore the world of IR sensors, their working priinciples , applications and  much more, if yes then read the blog and dive into the world of Infrared sensors**


## *What is an IR Sensor*
<p>We all have heard the term IR technology, we even use it in our day to day lives in TV and Air Conditioning remotes, but what we find ourselves asking is 'What is IR technonlogy and IR sensors?'</p>  
<p>To answer that question we must answer the question of what is IR, the term IR stands for **Infrared Radiation**, This type of radiation is present on the spectrum.

![Spectrum](https://cdn.sparkfun.com/assets/3/9/c/1/c/512bccd7ce395f4147000000.png)
</p> 
<p> The main advantages of IR sensor are their low power comsumption, simple design, and useful design. IR signals are undectable to human eye. In electronic spectrum given above. The wavelength of these waves typically range of 0.7um to 5 to 1000um.

There are 3 types of IRs:
1. Near-Infrared which is between 0.75um to 3um.
2. Mid Infrared which is between 3um to 6um.
3. Far Infrared which is between 6um to 1000um.

![IR](https://cdn.shopify.com/s/files/1/0559/1970/6265/files/what_is_ir_sensor_480x480.png?v=1655700063)
</p>

## *Working principles of an IR sensor*
<p>
This type of sensor includes IR sensor and IR photodiode, so combining the 2 components can be used as a photo-coupler. THe physics law used in the sensors are:

1. **Plank's Radiation Law:** Any object whose temperature is not equal to absolute zero(0k) emits radiation
2. **Stephan's Boltzmann Law:** The total energy emitted per unit surfacea area of a balckbody across all wavelengths per unit time is directly proportional to the 4th of the blackbody's thermodynamic temperature
3. **Wein's Displacement Law:** Objects of different temperature emit spectra that peak at different wavelengths that is inversely proportional to temperature.
</p>

## *How does an IR sensor work*
<p>
IR LED is 1 kind of transmitter that emits IR radiation. This LED has appearance of a standard LED, and the radiation is not visible to the naked eye. An infrared transmitter is used to detect the  radiation by the infrared recievers. These infrared recievers are available in photodiode form. IR photodiodes are different from regular photodiodes in that they only detect IR radiation.

When used as an IR transmitter and reciever, the wavelength of the reciever must match that of the transmitter. The transmitter is an Infrared LED and reciever is Infrared photodiode. The Infrared photodiode is activated by the infrared light produced by an infrared LED. 

Once the infrared transmitter generates emission, when it arrives at the object & some of the emission will reflect toward the infrared receiver. The sensor output can be decided by the IR receiver depending on the intensity of the response.
</p>

## *IR Proximity sensor working principle*
<p>
The working principle of the IR Proximity sensor is the same as the working principle of the IR sensor as explained above. IR is based on the principles of the optics. 

An IR proximity sensor works by applying a voltage to a pair of IR light-emmiting diodes which in turn, emit infrared light. This light propagates through the air and once it hits an object it is reflected towards the sensor. If the object is close, the reflected light will be stronger the than if the object is further away.

![IR_Proximity](https://cdn.shopify.com/s/files/1/0559/1970/6265/files/image5_480x480.jpg?v=1655700206)
</p>

## *Types of IR Sensors*
### 1. *Active IR Sensors*
![Active](https://cdn.shopify.com/s/files/1/0559/1970/6265/files/Active_IR_Sensor_480x480.jpg?v=1655700547)
<p>
This type of sensor includes both transmitter and reciever. In the majority of cases, a laser diode or LED is used as a light source. LEDs are used for non-imaging infrared sensors, while laser diodes are used foer using infrared sensors.

An infrared sensors works by emitting energy that is detected and recieved by the detector. To obtain the required data, it is further processed through signal processor. Reflectance and break beam sensors are the best examples of active infrared sensors.

</p>

![Act](https://cdn.shopify.com/s/files/1/0559/1970/6265/files/working_priciple_of_ir_sensor_480x480.jpg?v=1655700659)

### 2. *Passive IR Sensors*
![Passive](https://cdn.shopify.com/s/files/1/0559/1970/6265/files/Passive_IR_Sensor_480x480.jpg?v=1655700768)
<p>
The passive infrared sensor includes detectors only but they don't include a transmitter. These sensors make use a transmitter or an infrared source. This object emits the energy, which infrared recievers detect. After that, a signal processor is used to decode the signal and extract the necessary data. 
</p>

![Pas](https://cdn.shopify.com/s/files/1/0559/1970/6265/files/image9_64011fb4-a1ce-4afc-bb0e-b3337154e02a_480x480.png?v=1655700806)

<p>
The best examples of the sensors are pyroelectric detector, bolometer, thermocouple-thermopile, etc. These sensors are classified into 2 types thermal IR sensors and quantum IR sensors.
</p>

1. **Thermal Infrared Sensors**
![Thermal](https://cdn.shopify.com/s/files/1/0559/1970/6265/files/Thermal_Infrared_Sensor_480x480.png?v=1655700936)

   <p>
   These types of sensors are independent of wavelength and they utilize heat-like energy sources. These are slow along with response time as well as detection time.
   </p>

2. **Quantum Infrared Sensors**
![quantum](data:image/jpeg;base64,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)

   <p>
   These types of sensors depend on wavelengths and the response time and they have high detection. These kinds of an Infrared sensors need repeated cooling for exact measurement. 
  </p>

## Application of IR Sensors 
1. **Proximity Sensors**
    <p>
    These are used in smartphones to find the distance of objects. They use a principle called Reflective Indirect Incidence. Distance is calculated based on the intensity of radiation recieved.
    </p>
2. **Item Counter**
    <p>
    This uses the direct incidence method to count the items. Constant radiation between transmitter and reciever. As soon as the objects cuts the radiation, the item is detected and the count is increased. The same count is shown on a display system.
    </p>
3. **Radiation Thermometers**
    <p>
    It is 1 of the key applications of Infrared sensors. The working of a radiation thermometer depends on temperature and type of object.

    These have faster respons and easy pattern measurements. They can do measurements without direct contact with an object. 
    </p>
4. **Human Body Detection**
    <p>
    This method is used in intrusion detection, auto light switches, etc. An intrusion alarm system senses the temperature of the human body.

    If the temperature is more than the threshold value, it sets the alarms. It uses an electromagnetic system that is suitable for the human body to protect it from unwanted harmful radiation.
    </p>

## Conclusion
<p>
In this blog we have learned about the IR sensors, have revolutionized the way we interact with tecnology. By harnessing the power of infrared radiation, these sensors are able to detect the presence of the objects, measure distance, and even identify specific materials. From proximity sensors to thermal imaging systems, IR sensors have countless applications in field of Robotics, aerospace and medicine. 
</p>


