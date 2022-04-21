# Embedded door sensor circuit using Atmega328

## Requirements for project

### Atmega328
ATmega328 is an Advanced Virtual RISC (AVR) microcontroller. It supports 8-bit data processing. ATmega-328 has 32KB internal flash memory.ATmega328 has 1KB Electrically Erasable Programmable Read-Only Memory (EEPROM). This property shows if the electric supply supplied to the micro-controller is removed, even then it can store the data and can provide results after providing it with the electric supply. Moreover, ATmega-328 has 2KB Static Random Access Memory (SRAM). Other characteristics will be explained later. ATmega 328 has several different features which make it the most popular device in today’s market. These features consist of advanced RISC architecture, good performance, low power consumption, real timer counter having separate oscillator, 6 PWM pins, programmable Serial USART, programming lock for software security, throughput up to 20 MIPS etc.
* ATmega328 is an 8-bit, 28-Pin AVR Microcontroller, manufactured by Microchip, follows RISC Architecture and has a flash-type program memory of 32KB.
* It has an EEPROM memory of 1KB and its SRAM memory is 2KB.
* It has 8 Pins for ADC operations, which all combine to form PortA ( PA0 – PA7 ).
* It also has 3 built-in Timers, two of them are 8 Bit timers while the third one is 16-Bit Timer.
* It operates ranging from 3.3V to 5.5V but normally we use 5V as a standard.
* Its excellent features include cost-efficiency, low power dissipation, programming lock for security purposes, real timer counter with separate oscillator.


![Introduction-to-Atmega328_1](https://user-images.githubusercontent.com/101283423/164389163-1195d947-b9bf-488a-b686-f88cb605e2ea.png)
                                            
                            


### LED
A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons.


![LED](https://user-images.githubusercontent.com/101283423/164390742-05032e07-624a-4968-99aa-cb0acb376cd2.png)


### Switch
In electronics, an electronic switch is an electronic component or device that can switch an electrical circuit, interrupting the current or diverting it from one conductor to another. Electronic switches are considered binary devices because they can be on or off. When an electronic switch is on, it is considered closed in a circuit. When the switch is classified as off, the switch is open in the circuit.

Typically, electronic switches use solid state devices such as transistors, though vacuum tubes can be used as well in high voltage applications. Electronic switches also consist of complex configurations that are assisted by physical contact. Physical contact typically comes from pressing or flipping a switch with your hand, but other forms of contact like light sensors and magnetic field sensors are used to operate switches.
Different kinds of switches are used for different applications. Switches operated by a person are called hand switches. Hand switches consist of many types such as toggle switches, pushbutton switches, selector switches, and joystick switches. Another form is a motion switch; these are typically called limit switches. Limit switches are used to limit the motion of a machine. Limit switches are usually used for preventive safety measures so that a machine will cut off past a specified point. Two of the most common limit switches are lever actuator switches and proximity switches.

In industrial processes, process switches are used to monitor physical quantities. Switches such as speed, pressure, temperature, liquid level, liquid flow, and nuclear level switches are used to monitor vital information so that a process stays in control and never exceeds safety regulations.

![download](https://user-images.githubusercontent.com/101283423/164391114-f8d52725-3b07-4ab4-b911-ef4048480d58.jpg)

### Resister
A resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element. In electronic circuits, resistors are used to reduce current flow, adjust signal levels, to divide voltages, bias active elements, and terminate transmission lines, among other uses. High-power resistors that can dissipate many watts of electrical power as heat may be used as part of motor controls, in power distribution systems, or as test loads for generators. Fixed resistors have resistances that only change slightly with temperature, time or operating voltage. Variable resistors can be used to adjust circuit elements (such as a volume control or a lamp dimmer), or as sensing devices for heat, light, humidity, force, or chemical activity.

![10-ohm-500x500](https://user-images.githubusercontent.com/101283423/164391267-6de0c824-0bf2-46e0-affa-e6e06b8a1e9d.jpg)


### voltmeter
Voltmeter which is also known as voltage meter is an instrument that measures the voltage or potential difference among two points of an electronic or electrical circuit. Usually, the voltmeter is used for Alternating Current (AC) circuits or Direct Current (DC) circuits. Alternatively, Radio Frequency (RF) voltage can also be measured by specialized voltmeters.

![download](https://user-images.githubusercontent.com/101283423/164391577-1231547a-e3d0-44ac-a634-70728c310df4.png)


### Fixed Volt
A fixed voltage regulator produces a fixed DC output voltage, which is either positive or negative. In other words, some fixed voltage regulators produce positive fixed DC voltage values, while others produce negative fixed DC voltage values.


# High Level Requirements
* Switch

# Low Level Requirements
* LED
* Resister-10ohm
* Voltmeter
* Atmega328
* Fixed voltmeter
