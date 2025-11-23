The system uses an LDR sensor to sense variations in ambient light intensity. The analog signal from the
LDR is compared with a reference voltage using an LM311 voltage comparator, producing a clean digital output.
This output is then processed through an ADC to enable further digital control and logic implementation.
To manage the control logic, a 74LS148 priority encoder is used to convert the signals into 3-bit digital
data. A 7404 NOT gate is incorporated to modify the most significant bit (MSB) as required by the decision
logic. Based on these digital signals, the system decides whether the headlights should operate in dim or bright
mode.
In dim mode, 2 lights are switched on, while in bright mode, 5 lights are activated. This priority encoder-
based switching arrangement ensures efficient control of headlight intensity without the need for complex power
devices.
