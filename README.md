# 4-LED Light Intensity Meter Circuit
The proposed 4-LED Light Intensity Meter circuit uses comparators in the form of operational amplifiers of the LM324 IC. This IC is much more versatile than the other opamp counterparts due to its higher voltage tolerance and quad op amp in one package. All four operational amplifiers were used in the proposed LED light intensity meter circuit. As can be seen from the circuit diagram, the configuration is simple, but the result is effective.

## Circuit Diagram
In this the non-inverting pins of all four op amps are clamped to a fixed reference level determined by the voltage divider circuit, which is not critical and is decided by the LDR. The inverting pins of the opamps are configured as the sensing inputs and are terminated with variable resistors or the potentiometers. The given Light Intensity Meter is configured in the "bar graph" mode, i.e., the cathodes of all the LEDs are connected to the ground or the negative line. If we want to configure it in the "dot" mode (i.e., only one LED glows at any instant indicating the relevant voltage/intensity level), then simply disconnect the cathodes of all the LEDs from the existing points and connect them as shown in the circuit diagram.

## Working
The circuit works by sensing the light intensity on the LDR and producing a voltage signal. The voltage is compared with a fixed reference voltage using the operational amplifiers, and the output drives the LED corresponding to the intensity level. The LED glows brighter as the intensity increases.

## Usage
The 4-LED Light Intensity Meter circuit can be used in various applications that require light sensing, such as automatic street lights, security systems, and more.

## Future Improvements
Possible future improvements for this project include adding an automatic dimming feature or integrating it with a microcontroller to control the output.
