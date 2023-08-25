## Penngineering Projects

### Metal Detector
*A working metal detector was designed, simulated, built and demonstrated from scratch, as part of the ESE 3190 Final Project.*

<span style="color:green">Oscillators</span> were used to produce output sinusoidal waveforms whose frequency difference, w<sub>1</sub>-w<sub>2</sub>, increased as a function of the proximity of the metal to the detector. A <span style="color:green">mixer</span> combined the oscillation frequencies into one signal, a <span style="color:green">CS amplifier</span> produced different mathematical combinations of the oscillation frequencies, including the frequency difference, w<sub>1</sub>-w<sub>2</sub>, which was filtered by a <span style="color:green">low pass filter</span>, amplified by the <span style="color:green">driver</span> and outputted by the <span style="color:green">speaker</span>.

Multiple simulations were conducted on LTSpice and the different stages of the metal detector circuitry were breadboarded in previous labs before the layout of the components on Altium was done for the creation of a printed circuit board (PCB). 

> Skills: PCB Design & Assembly, Altium Designer, LTSpice, Oscilloscope

### Hand-Powered Hand
*An animatronic hand was made that mimics the gestures of a human hand and communicates with it wirelessly, as part of the ESE 3500 Final Project.*

This involved three parts.
1. <span style="color:green">Sensing</span> i.e. measuring accurate readings of the motion of the human hand using a glove integrated with flex sensors and the Arduino's ADC.
2. <span style="color:green">Actuation</span> i.e. the corresponding movement of a mechanically designed hand using servo motors.
3. <span style="color:green">Wireless</span> i.e. involves transmission between the Arduino attached to the glove and the mechanical hand using nrf24L01 modules.
In all, the project hopes to prove useful in applications where human hands cannot be used in hazardous situations, telecommunications, and physical disability. 

> Skills: C, Microcontrollers, Wireless Communication, Mechanical Design

### Coupled Learning Neural Network
> Skills: PCB Design & Assembly, Altium Designer

### Closed-Loop Holographic Control of Nanorobots
*Nanorobots were holographically illuminated and controlled in the field of view of a spatial light modulator (SLM) using a laser 🚨 and microscope 🔬. This was my project during my summer at Miskin Labs.*

This involved three parts.
1. Investigating the <span style="color:green">Gerchberg-Saxton Algorithm</span> for the retrieval of phase information from intensity measurements and enabling the patterning of laser light.
2. Using span <span style="color:green">Computer Vision</span> (OpenCV package) to identity nanorobots.
3. Fixing alignment issues between the DSLR and SLM frame using <span style="color:green">matrix transformations</span>, to shine light precisely on the nanorobots.

> Skills: Python, OpenCV, Optics, Spatial Light Modulator

### Pong
*Pong is one of the first ever computer games 🎮 created. It's quite simple - two paddles and a ball 🏓 and the goal is to defeat the opponent by making them lose the ball. This was made as part of a ESE 3500 lab.*

In this project, a LCD screen 🖥 is programmed using an Arduino Uno and SPI, and its graphics library is written with the help of some given .h files. A buzzer, joystick, LEDs, and a logic level shifter is also used. The NodeMCU board is used for wireless control of the joystick.

> Skills: C, Microcontrollers

### Theremin
*Theremin is an electronic musical 🎵🎶 instrument controlled without physical contact by the performer, and in this case, controlled by the distance of the user's hand 🖐 from an ultrasonic sensor. This was made as part of a ESE 3500 lab.*

Input capture was used to measure distance and hence pulse width. Timers, PWM, ADC and output compare was used to generate music of different frequencies through the buzzer. A photoresistor was added to control volume with light, and both continuous and discrete modes of operation were implemented.

> Skills: C, Microcontrollers

### Morse
*This device allows you to translate a Morse code signal to its alphanumeric representation. This was made as part of a ESE 3500 lab.*

It works by first detecting an incoming signal using an input switch 🎚(using polling or interrupts), then translating and displaying the hidden message in ASCII onto a serial port. It also lights up LEDs based on what signals were received.

> Skills: C, Microcontrollers
