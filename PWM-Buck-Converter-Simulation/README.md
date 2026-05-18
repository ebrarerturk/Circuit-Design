# PWM Buck Converter Simulation

This project is a simple PWM-controlled buck converter simulation built in LTspice.

The circuit includes:
- PWM-controlled switch
- Schottky diode
- Inductor-capacitor (LC) filter
- Resistive load

The goal was to better understand how a DC-DC buck converter behaves during switching and transient operation.

## What I observed during simulation

At the beginning, the output voltage had:
- large overshoot,
- noticeable oscillations,
- unstable settling behavior.

To improve the response, I adjusted some component values and PWM settings.

## Changes I made

- Reduced the PWM duty cycle to lower the average output voltage
- Increased the inductor value to reduce current ripple
- Increased the capacitor value to smooth the output voltage
- Changed the load resistance to improve stability
- Increased simulation time to better observe transient behavior

After these adjustments, the output became more stable and the oscillations were reduced.

## What I practiced

- PWM switching
- Basic buck converter operation
- LC filtering
- Transient analysis in LTspice
- Observing overshoot and damping behavior
- Simple circuit optimization through simulation

## Software

- LTspice
