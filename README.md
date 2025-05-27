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
​
