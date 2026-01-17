# Automatic-street-light-system-by-using-Arduino-Nano
This project uses an Arduino Nano to automate street lights based on ambient light conditions.
AUTOMATIC STREET LIGHT SYSTEM


Introduction

Automation plays an increasingly very important role in the world economy and in daily life.Automatic systems are being preferred over any kind of manual system. We can also call it an “SMART STREET LIGHT SENSING”. Intelligent light sensing refers to public street lighting that adapts to movement by pedestrians, cyclists and cars. Intelligent street lighting, also referred to as adaptive street lighting, dims when no activity is detected, but brightens when movement is detected. This type of lighting is different from traditional, stationary and illumination, or dimmable street lighting that dims at predetermined times.

 The method operates by set up an optical control circuit, change the resistance by using of light sensitive device to control street lamps light up automatically at dusk and turn off automatically after dawn in the morning. Due to the technological development nowadays, road lighting can be categorized according to the installation area and performance, for an example, lighting for traffic routes, lighting for subsidiary roads and lighting for urban center and public amenity areas.
  
Theory

Smart Street Lighting

Street lights are doing more than ever in today’s smart cities. With digital networks and embedded sensors, they collect and transmit information that help cities monitor and respond to any circumstance, from traffic and air quality to crowds and noise. They can detect traffic congestion and track available parking spaces. 

Those very same networks can remotely control LED lights to turn on and off, flash, dim and more, offering cities a chance to maximize low-energy lighting benefits while also improving pedestrian and bicyclist safety. With street lights creating a network canopy, those networks of data can be used by more than just lighting departments, empowering even schools and businesses via a lighting infrastructure that brightens the future of the digital city.

Smart lighting helps cities save energy, lower costs, reduce maintenance—all while better serving citizens and reducing energy use and CO2 emissions. Automation and networked control can further increase your energy savings and reduce maintenance spending. Networked street lighting built on a scalable platform can reduce crime up to 10%and make roadways safer through improved visibility. Leveraging intelligent control systems can rapidly increase lighting efficiencies and traffic management.

Arduino Uno R3

It is a microcontroller board based on the ATmega328. Arduino is an open-source,prototyping platform and its simplicity makes it ideal for hobbyists or novice to use as well as professionals. The Arduino Uno has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz crystal oscillator, a USB connection, a power jack,
an ICSP header, and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with AC-to- DC adapter or battery to get started.

The Arduino Uno R3 uses an ATmega16U2 instead of the 8U2 found on the Uno (or the FTDI found on previous generations). This allows for faster transfer rates and more memory. No drivers needed for Linux or Mac (in file for Windows is needed and included in the Arduino IDE), and the ability to have the Uno show up as a keyboard, mouse, joystick, etc. The Arduino  Uno differs from all preceding boards in that it does not use the FTDI USB-to-serial driver chip. Instead, it features the Atmega8U2 microcontroller chip programmed as a USB- to-serial  converter.

The Uno R3 also adds SDA and SCL pins next to the AREF. In addition, there are two new pins placed near the RESET pin. One is the IOREF that allow the shields to adapt to the voltage provided from the board. The other is a not connected and is reserved for future purposes. The Uno R3 works with all existing shields but can adapt to new shields which use these additional pins. "Uno" means one in Italian and is named to mark the upcoming release of Arduino 1.0.

Preferred quality and originals are made in Italy. The Arduino Uno and version 1.0 will be the reference versions of Arduino, moving forward. The Uno is the latest in a series of USB Arduino boards, and the reference model for the Arduino platform.





Features of the Arduino UNO:

 Microcontroller: ATmega328
 Operating Voltage: 5V
 Input Voltage (recommended): 7-12V
 Input Voltage (limits): 6-18V
 Digital I/O Pins: 14 (of which 6 provide PWM output)
 Analog Input Pins: 6
 DC Current per I/O Pin: 40 mA
 DC Current for 3.3V Pin: 50 mA
 Flash Memory: 32 KB of which 0.5 KB used by bootloader
 SRAM: 2 KB (ATmega328)
 EEPROM: 1 KB (ATmega328)
 Clock Speed: 16 MHz









IR sensor


An infrared sensor is an electronic device that emits in order to sense some aspects of the surroundings. An IR sensor can measure the heat of an object as well as detects the motion as well as the presence of an object due to intervention or interruption. These type of sensors measure only infrared radiation, rather than emitting it that is called as a passive IR sensor. Usually in the infrared spectrum, all the objects radiate some form of thermal radiations. These types of radiations are invisible to our eyes that can be detected by an infrared sensor.The emitter is simply an IR LED (Light Emitting Diode) and the detector is simply an IR photodiode which is sensitive to IR light of the same wavelength as that emitted by the IR LED. When IR light falls on the photodiode, the resistances and these output voltages, change in proportion to the magnitude of the IR light received.
An IR sensor is a device which detects IR radiation falling on it. There are numerous types of IR sensors that are built and can be built depending on the application. Proximity sensors (Used in Touch Screen phones and Edge Avoiding Robots), contrast sensors (Used in Line Following Robots) and obstruction counters/sensors (Used for counting goods and in Burglar Alarms) are some examples, which use IR sensors. Working Mechanism
An IR sensor is basically a device which consists of a pair of an IR LED and a photodiode which are collectively called a photo-coupler or an opto-coupler. The IR LED emits IR radiation, reception and/or intensity of reception of which by the photodiode dictates the output of the sensor. Now, there are so many ways by which the radiation may or may not be able to reach the photodiode. 

Direct incidence

We may hold the IR LED directly in front of the photodiode, such that almost all the radiation emitted, reaches the photodiode. This creates an invisible line of IR radiation between the IR LED and the photodiode. Now, if an opaque object is placed obstructing this line, the radiation will not reach the photodiode and will get either reflected or absorbed by the obstructing object. This mechanism is used in object counters and burglar alarms.

High school physics taught us that black color absorbs all radiation, and the color white reflects all radiation. We use this very knowledge to build our IR sensor. If we place the IR LED and the photodiode side by side, close together, the radiation from the IR LED will get emitted straight in the direction to which the IR LED is pointing towards, and so is the photodiode, and hence there will be no incidence of the radiation on the photodiode. Please refer to the right part of the illustration given below for better understanding. But, if we place an opaque object in front the two, two cases occur:


Reflective Surface

If the object is reflective, (White or some other light color), then most of the radiation will get reflected by it, and will get incident on the photodiode. For further understanding, please refer to the left part of the illustration below.

Non-reflective Surface

If the object is non-reflective, (Black or some other dark color), then most of the radiation will get absorbed by it, and will not become incident on the photodiode. It is similar to there being no surface (object) at all, for the sensor, as in both the cases, it does not receive any radiation.


Light Emitting Diode

A light-emitting diode (LED) is a two-lead semiconductor light source. It is p-n junction diode that emits light when activated. The long terminal is positive and the short terminal is negative. When a suitable current is applied to the leads, electrons are able to recombine with electron holes within the device, releasing energy in the form of photons. This effect is called electroluminescence, and the color of the light (corresponding to the energy of the photon) is determined by the energy band gap of the semiconductor. LEDs are typically small (less than 1 mm2 ) and integrated optical components may be used to shape the radiation pattern. LEDs are versatile semiconductor with a number of attributes which make them perfect for most applications. Their features include:  Long Life: LEDs can last over 100,000 hours (10+ years) if used at rated current  No annoying flicker as we experience with fluorescent lamps. LEDs are impervious to heat, cold, shock and vibration. LEDs do not contain breakable glass.

 Solid-State, high shock and vibration resistant  Extremely fast turn on/off times  Low power consumption puts less load on the electrical systems increasing battery life.Here we have used the most common 5mm white light. White LEDs are perfect for replacing inefficient incandescent bulbs in night lights and path lights.

SPECIFICATION:

Intensity: 28,500mcd Voltage: 3.0v-3.3v
Color Freq: x=31 y=32 Typical: 3.1v
Viewing Angle: 48º Current: 20mA

Automatic street lights are lighting systems that turn on and off based on ambient light levels. They typically use light sensors to detect when natural light diminishes, activating the lights at dusk.
These systems can also include timers and motion sensors to enhance efficiency. 
By conserving energy during daylight hours, they contribute to sustainability. 
Additionally, they improve safety and visibility for pedestrians and drivers at night.




Hardware components:

 Arduino nano
 3* IR sensor 
 3* LED lights
 1*LDR module 
 Jumper wires
 Breadboard 
 Power supply 


Circuit connection 

 IR sensors 
 VCC to Arduino nano 5v
GND to Arduino nano 0v
OUT to Arduino digital pins 
IR1-D8
IR2-D12
IR3-D13
LED lights 
Anode to Arduino nano digital pins
LED 1- D3
LED 2- D5
LED 3-D6
Cathode to GND 
LDR Module 
VCC to arduino 5V
GND to arduino 0v
OUT to arduino digital pin D7





Code for Arduino nano 


int IR1 = 8; int IR2 = 12; int IR3 = 13; int LDR = 7; int led1 = 3; 
int led2 = 5;

int led3 = 6;

int val1;

int val2;

int val3;

int val4;

void setup()

{

pinMode(IR1,INPUT);

pinMode(IR2,INPUT);

pinMode(IR3,INPUT);

pinMode(LDR,INPUT);

pinMode(led1,OUTPUT);

pinMode(led2,OUTPUT);

pinMode(led3,OUTPUT);

}
void loop() {

val1 = digitalRead(IR1);

val2 = digitalRead(IR2);

val3 = digitalRead(IR3);

val4 = digitalRead(LDR);

if(val1==1&&val4==0&&val2==1&&val3==1)

{

digitalWrite(3,LOW);

digitalWrite(5,LOW);

digitalWrite(6,LOW);
}

else if(val1==1&&val4==1&&val2==1&&val3==1)

{

analogWrite(3,20);

analogWrite(5,20);

analogWrite(6,20);

}
else if(val1==0&&val4==1&&val2==1&&val3==1)

{

analogWrite(3,500);

analogWrite(5,20);

analogWrite(6,20);

}

else if(val1==1&&val4==1&&val2==0&&val3==1)

{
analogWrite(3,20);
analogWrite(5,500);
analogWrite(6,20);
}
else if(val1==1&&val4==1&&val2==1&&val3==0)
{
analogWrite(3,20);
analogWrite(5,20);

analogWrite(6,500);

}

}




Explanation:

1.⁠ ⁠The program reads the IR sensor values and LDR module value.
2.⁠ ⁠If the LDR value is below the threshold (indicating nighttime), the program checks for motion detection using the IR sensors.
3.⁠ ⁠If motion is detected, the program turns on the corresponding LED(s).
4.⁠ ⁠If no motion is detected, the program turns off the LED(s).
5.⁠ ⁠During daytime (LDR value above threshold), the program turns off all LED(s).

Adjustments:

•⁠  ⁠Adjust the threshold value for the LDR module based on your environment's lighting conditions.
•⁠  ⁠Adjust the delay time to optimize the system's response.
•⁠  ⁠You can modify the program to use more advanced features, such as:
    - Motion detection timing adjustments
    - LED brightness control

Application and Advantages
 The street light control circuit can be used in normal roads, highways, express ways etc. 
The project can also be used in parking areas of malls, hotels, industrial lighting, etc.
 If the lighting system implements all LED lights, the cost of the maintenance can be reduced as the life span and durability of LEDs is higher than Neon based lights which are normally used as street lights.
 As the lights are automatically turned ON or OFF, huge amount of energy can be saved.
 This system less costly, less installation and maintenance cost and more efficient as compared to the others system.

Limitations and Future Work

 This system can be used for only one way traffic. A highway might be covered by this system on dual system installation on both side.The system does not have any automatic fault detector.  Pole damage detection with the addition of suitable sensor can be implemented.

Conclusion


By using Smart Street light, one can save surplus amount of energy which is done by
replacing sodium vapor lamps by LED and adding an additional feature for security
purposes. It prevents unnecessary wastage of electricity, caused due to manual switching of streetlights when it’s not required. It provides an efficient and smart automatic streetlight control system with the help of IR sensors. It can reduce the energy consumption and maintains the cost. The system is versatile, extendable and totally adjustable to user needs. The system is now used only for One way traffic in highways.  Continuous uses of LDR and IR sensors even in day time. Not switched on before the sunset. The Smart light system can be further extended to make the current system in two-way traffic, making the system more flexible in case of rainy days and introduction of ways to control the lights through GSM based service.























