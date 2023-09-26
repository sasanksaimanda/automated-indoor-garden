# automated indoor garden
 
#INTRODUCTION:
At the present time, in an era with sophisticated technology, improving the quality of human
life.There is a demand for diverse, and more practical automated technologies that can reduce
or replace the need for human labour in daily tasks and jobs. This article introduces one such
system, the “AUTOMATIC INDOOR GARDENER”system, which is basically a model of
irrigation facility control that integrates with Rasberry pi Software and sensor technology to
monitor soil moisture with a 12V Water-pump to produce a smart switching device to assist
millions of people.
This automatic irrigation system senses the moisture content of the soil and automatically
switches the pump when the power is on. A proper usage of irrigation system is very
important because the main reason is the shortage of land reserved water due to lack of rain,
unplanned use of water as a result large amounts of water goes waste. This is why we utilise
this automated plant watering system, which is effective in all kinds of weather conditions.
Nowadays,There are several irrigation systems available on the market that use an automated
system. However, the system cannot be installed in a small home garden because of the high
cost of the equipment. To track the growth of the plants using the irrigation method that
several researchers have created, a sophisticated and expensive computer is required. Most
miniature gardens in residential areas are not protected by house roofs, leaving them open to
weather changes like heavy rain or extremely hot temperatures. The growth of the plants in
the garden may be impacted by these different environmental factors. To make sure the plants
are developing properly, the homeowner should periodically check on this little garden.
However, it could be challenging for a homeowner to keep an eye on their plants if they are
gone for a long period. To monitor and manage the system that can water their plant from
different locations, one system should be constructed.

#COMPONENTS USED:

Raspberry Pi 3 B:
The Raspberry Pi range of small single-board computers (SBCs) was created by the Raspberry
Pi Foundation in partnership with Broadcom. The Raspberry Pi project's primary goal was to
promote the study of fundamental computer science in classrooms and in developing countries.
Because it was utilised more extensively than anticipated, the original model sold outside of
the market it was designed for for uses like robotics. It is commonly used in many different
industries, including weather monitoring, because to its low cost, adaptability, and open
architecture. It is often used by computer and electrical hobbyists since it supports the HDMI
and USB standards.

Raspberry Pi 3 Model B is the earliest model of the third-generation Raspberry Pi.

Specifications:
Quad Core 1.2GHz Broadcom BCM2837 64bit CPU
1GB RAM
BCM43438 wireless LAN and Bluetooth Low Energy (BLE) on board
100 Base Ethernet
40-pin extended GPIO
4 USB 2 ports
4 Pole stereo output and composite video port
Full size HDMI
CSI camera port for connecting a Raspberry Pi camera
DSI display port for connecting a Raspberry Pi touchscreen display
Micro SD port for loading your operating system and storing data
Upgraded switched Micro USB power source up to 2.5A
Fig1-Raspberrypi

Soil Moisture Sensor:
The moisture content of the soil is measured by this sensor using a few soil properties, such as
the electrical resistance, dielectric constant, or interaction with neutrons.
The two probes enable current to pass through the soil in order to calculate the resistance value,
which in turn yields the moisture value. A excellent conductor of electricity, or one with
reduced resistance, is moist soil. Consequently, a significant moisture level is seen. Because
dry soil has higher resistance and is a poor conductor of electricity, the moisture content will
be low.
Fig2-Soil moisture

Resistors:
A resistor is a passive, two-terminal electrical element that creates electrical resistance in
circuits. In electronic circuits, resistors provide a range of functions, such as regulating signal
levels, reducing current flow, biassing active components, splitting voltages and terminating
transmission lines.

12v Water Pump:
A pump is a mechanical tool used to physically move fluids (liquids, gases, or occasionally
slurries) by converting electrical energy into hydraulic energy.

Fig3-motor

Diode:
A diode is a two-terminal electrical component that primarily conducts current in one direction
(asymmetric conductance); it has low resistance in one direction (ideally zero resistance) and
high resistance in the other direction (ideally infinite resistance).
Bridge Rectifier:
A Bridge Rectifier is a kind of full-wave rectifier that effectively transforms alternating current
(AC) to direct current (DC) by employing four or more diodes in a bridge circuit arrangement.

Relay:
Relays are switches that are controlled by electricity. It is made up of a set of working
contact terminals and a set of input terminals for one or more control signals. Relays are
utilized when a circuit has to be controlled by a separate low-power signal or when several
circuits need to be controlled by a single signal.
Fig4-relay

Capacitors:
By building up electric charges on two adjacent surfaces that are separated from one another, a
capacitor is a gadget that stores electrical energy in an electric field. It is a two-terminal inactive
electrical component.
Light Bulb:
A light-bulb produces light from electricity. They can be used to show an electronic equipment
is on, to direct traffic, and for heat in addition to lighting a dark area.

NPN Transistor
A transistor is a semiconductor device that amplifies or switches power and electrical signals.
A transistor that employs both electrons and holes as charge carriers is known as a bipolar
transistor.
A p-type semiconductor is sandwiched between two n-type semiconductors to create the
bipolar NPN transistor. In this case, electrons make up the majority of the charge carriers
while holes make up the minority.

Step-Down Transformer:
A transformer is a static device with no moving elements that transfers electrical power
between circuits while varying the voltage and current but not the frequency. Step-up
transformers and step-down transformers are two different types of transformers that can be
categorised according to their use.
A Step Up transformer is a device that scales up the input voltage by converting the low primary
voltage to the high secondary voltage.
On the other side, a step-down transformer reduces the input voltage, so that the secondary voltage is
lower than the main voltage
working principle
The main working principle of this system is to connect the previously embedded soil
moisture sensor to the Raspberry-pi microcontroller, which is also connected to other
electronic components.
Soil moisture is measured by the sensor, which sends information and parameters about soil
moisture to the microcontroller, which controls the pump.
If the level of soil moisture falls below a certain threshold, the microcontroller sends a signal
to the relay module, which then activates a pump and delivers a certain amount of
water to the plant.
When enough water is delivered, the pump stops working. The power supply's task is to
power the entire system, and the recommended voltage should respect the microcontroller's
input supply range, which is 7V to 12V.
A relay module is a simple circuit made up of a single transistor, several resistors, diodes, and
a relay that is digitally controlled by a microcontroller. Because the entire system must be
housed in a small box, the Raspberry-pi is an ideal microcontroller for this task due to its
small size and high performance.
A moisture level sensor is attached to the soil of the plant for the automatic plant watering
system, and when the sensor's reading falls below a pre-set value, the pump is activated.
Fig5-flowchart

CONCLUSION:
The Raspberry Pi has been successfully used to create a “AUTOMATIC INDOOR
GARDENER” by connecting it to a single relay module, a 12 v Water pump, a soil moisture
sensor,Step-Down Transformer,Resistor,Capacitor,Diode and a Light bulb. It was created by
integrating functionality from every piece of hardware used.Every module's presence has
been thoughtfully considered and arranged, which helps the unit function as best it can.
The water content or moisture content of the various plants is measured by the soil moisture
sensors. The moisture sensor alerts the micro-controller if the moisture level is below the
acceptable level, which causes the water pump to switch on and feed the appropriate plant
with water. The mechanism automatically stops when the target moisture level is attained,
and the water pump is shut off.
This System may be used to efficiently use water resources in any small-scale agricultural
sector at a reasonable cost. A user can handle to remotely operate the irrigation system by
integrating Android interface apps in mobile.
As a result, the system's functioning has been carefully tested and is deemed to work
effectively and adopting this intelligent watering system greatly reduces the need for human
involvement and it also saves the time and water usage which could be so advantageous to us.
