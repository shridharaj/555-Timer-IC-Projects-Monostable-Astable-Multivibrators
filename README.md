# 555-Timer-IC-Projects-Monostable-Astable-Multivibrators
## Aim
To generate a 0.5 ms pulse with a 555 timer IC in monostable state. and create an astable multivibrator circuit that activates a monostable multivibrator using signal conditioning circuits.
## Theory
An electronic circuit with one stable state and one quasi-stable state is called a monostable multivibrator. It briefly transitions to the quasi-stable state in response to an external pulse, then returns to the stable state after a predefined amount of time. This circuit is frequently utilised in timing applications, including digital logic timing, delay circuits, and pulse generation.The monostable multivibrator, which is commonly implemented using logic gates, a 555 timer, or an op-amp, produces a single output pulse with a fixed duration for each trigger input. The output pulse's duration is determined by the circuit's components, which are typically a resistor (R) and a capacitor (C).
For a 555 timer, 𝑇 = 1.1 × 𝑅 × 𝐶
## working  Principle
There is only one stable state in a monostable multivibrator. The circuit momentarily enters a quasi-stable state and generates a high (or low) output pulse in response to an external trigger. Without any additional input, the circuit automatically returns to its stable state after a predetermined amount of time, which is dictated by the RC time constant.In a monostable multivibrator with a 555 timer:At first, the output is LOW (stable state).The internal flip-flop of the timer is set to HIGH when a negative trigger pulse is applied to the TRIG pin (pin 2).Through a resistor, the timer-connected capacitor begins to charge.
When the voltage of the capacitor reaches 2 3 3 2, Once the capacitor voltage reaches 2 3 3 2 of the supply voltage, the timer resets the flip-flop, and the output returns to LOW (stable state).
The pulse width (T) is given by:
𝑇=1.1×𝑅×𝐶
This pulse width is independent of the trigger duration, making the monostable multivibrator ideal for generating precise time delays or one-shot pulses.
​## Circuit Diagram 
![445184786-f09d2014-f234-4cf1-947f-79f882f99862](https://github.com/user-attachments/assets/1a45c58c-e8ab-489b-a06c-a2dc841ee3d2)
## Calculation:
Given that T=0.5ms and assume c=1uF.
T=1.1RC
R = 0.5mS/(1.1×1uF) = 454.54 Ohm.
## Procedure
Build the circuit according to the Circuit Diagram.Use the ton=1.1RC formula to get the resistor R and capacitor C. In simulation, we used a signal generator to trigger the circuit.Analyse the capacitor's charging and discharging voltage over time. Examine the tonne period when input is initiated.
## output waveform
![445185357-141243cc-a94a-4485-b145-532742e47138](https://github.com/user-attachments/assets/98e34820-ba8b-4912-bcf1-ced624868cf3)
The first waveform is the Monostable Multivibrator's triggering pulse, the second waveform is the voltage across the capacitor, and the third waveform is the output pulse, which is 0.5 milliseconds in duration.
## Astable Multivibrator And Monostable Multivibrator Using 555 Timer
## Given question
Generate a waveform with pulse width of 0.5 ms under different trigger conditions using 555 timer IC.
## Circuit Design and calculation
![WhatsApp Image 2025-05-27 at 23 10 01_694565fb](https://github.com/user-attachments/assets/b13ebcd3-d9e7-4b3e-88a3-fccf19411f12)
![WhatsApp Image 2025-05-27 at 23 09 47_b218c032](https://github.com/user-attachments/assets/65e7ddf9-c282-41e3-b49d-6be54cddcd90)
![Screenshot 2025-05-27 230733](https://github.com/user-attachments/assets/ebb0d871-0eb6-4bdc-928a-e4c2d9e8db1f)
## CASE1:
![Screenshot 2025-05-27 231304](https://github.com/user-attachments/assets/2ce7c7f8-95db-4e55-9b43-b0e203dc195d)
as we see in the above waveform the First waveform is the output of monostable multivibrator with pulse width of 0.5 ms. and the 2nd one is output of positive clipper circuit and the third one is output of differentiator circuit and lastely is the output of astable multivibrator.
## Case 2:
For ton = 0.8 ms and toff = 0.3 ms, Period = 0.5 ms
![Screenshot 2025-05-27 231525](https://github.com/user-attachments/assets/522db878-1595-44d5-afb4-2bd4404a81fe)
## CASE3:
For ton = 0.5 ms and toff = 0.2 ms, Period = 0.5 ms
![Screenshot 2025-05-27 231646](https://github.com/user-attachments/assets/544a4193-2ae3-4b8f-969b-051b53d6c857)
## INFERENCE
The astable multivibrator switches between two unstable states all the time without any outside help. The circuit makes a square wave output with a certain frequency and duty cycle that depend on the values of the resistors and capacitors used.
This shows that an astable multivibrator can work as a free-running oscillator, which is useful for making pulses, clock signals, flashing LEDs, and tones.
## Simulation in Virtual Lab Astable Multivibrator
1. Connect the components as mentioned below: L1-L12, L14-L12, L16-L12, L4-L9, L8-L9, L10-L19, L3-L17, L11-L13, L7-L19, L6-L13, L2-L13, L5-L15, L18-L9.(For eg. click on 1 and then drag to 12 and so on.)
2. Click on 'Check Connection' button to check the connections.
3. If connected wrong, click on the wrong connection. Else click on 'Delete all connection' button to erase all the connections.
4. Intially set R a=3.3 kΩ, R b=6.8kΩ, C=0.1µf, Vcc=5 V.
5. Click on "Calculate" button.
6. Now note the output voltage.
7. Click on "Plot" button to plot Output Voltage, Capacitance Voltage
8. Click on "Clear" button to clear the data.
9. Repeat the experiment for another set of resistance value.
10. Set the Resistance (Ra) value (1 kΩ - 10 kΩ).
11. Set the Resistance (Rb) value (1 kΩ - 10 kΩ).
12. Set the Capacitance (C) value (0.1 µf - 10 µf) .
13. Set supply voltage (Vcc).
## Circuit Diagram
![Screenshot 2025-05-27 232658](https://github.com/user-attachments/assets/2916c71c-039b-4c74-8421-5ee9ee1556aa)
## Otuput Waveform
Voltage Across the Capacitor:
![Screenshot 2025-05-27 232810](https://github.com/user-attachments/assets/33256655-a32c-4597-b469-c276b09acef4)
## Output Waveform: 
![Screenshot 2025-05-27 232917](https://github.com/user-attachments/assets/850befd3-5796-4295-93ff-3c984fbb2217)



