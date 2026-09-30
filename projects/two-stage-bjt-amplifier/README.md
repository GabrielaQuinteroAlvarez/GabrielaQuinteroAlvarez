# Two-Stage BJT Amplifier Design

## Overview
This electronics design combines a **common-emitter (CE) amplifier** with a **common-collector (CC) emitter-follower stage**.

The CE stage provides voltage gain, while the CC stage acts as a buffer to reduce the effect of load variation on the first stage.

## Design Process
1. Determine the required overall voltage gain
2. Design the common-emitter bias point
3. Calculate transistor small-signal parameters
4. Determine resistor values
5. Estimate the maximum output swing
6. Select an emitter current for the buffer stage
7. Design the common-collector stage
8. Check loading between stages
9. Simulate the complete circuit
10. Compare simulation results with hand calculations

## Engineering Concepts
- BJT biasing
- Common-emitter gain
- Common-collector buffering
- Input resistance
- Output resistance
- Loading effects
- Small-signal transistor models
- Voltage gain
- Circuit tolerances

## Tools
**Keysight ADS · Hand Calculations · Analog Circuit Simulation**

## What I Learned
This project showed me why amplifier design is more than achieving a target gain. A useful circuit also has to handle loading, bias stability, signal swing, and component tolerances.
