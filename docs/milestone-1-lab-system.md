# Milestone 1 Lab System Build Plan

## Objective
Build a benchtop oxygen-transfer validation rig that can measure whether a structured membrane interface improves oxygen transfer into a controlled liquid medium compared with passive diffusion.

## Milestone Outcome
Produce the first real dataset for the BioPlant Aquatic Habitat project.

## System Architecture
The lab system has six modules:

1. Test Chamber
- Transparent tank or sealed acrylic vessel
- Working volume: 5–20 liters
- Ports for gas line, sensor cable, and circulation loop

2. Gas Source Module
- Preferred: medical oxygen cylinder with regulator
- Alternate: aquarium air pump for baseline tests
- Flow control valve and flow meter

3. Membrane Interface Module
- Replaceable membrane cassette
- Flat-sheet or hollow-fiber membrane holder
- Initial materials: silicone membrane, PTFE membrane, or microporous polymer membrane

4. Circulation Module
- Low-flow pump
- Adjustable flow range: 0.5–5.0 L/min
- Recirculation tubing

5. Measurement Module
- Dissolved oxygen (DO) meter or optical DO sensor
- Temperature sensor
- Stopwatch or digital logger

6. Data Capture Module
- Spreadsheet logging sheet
- Trial ID tracking
- Photo/video documentation for setup repeatability

## Experimental Layout
Gas source -> regulator -> flow meter -> membrane cassette
Liquid chamber -> circulation pump -> membrane cassette -> return to chamber
DO sensor placed in chamber away from direct gas entry point
Temperature sensor placed in chamber centerline

## Build Specification
### Chamber
- 10 L clear acrylic or food-grade polycarbonate vessel
- Lid with sealed ports
- Drain valve optional

### Membrane Cassette
- PVC, acrylic, or 3D-printed frame
- Replaceable gasket
- Effective membrane area target: 100–400 cm^2 for early trials

### Pump
- Low-shear peristaltic or small recirculation pump
- Stable continuous operation for 30–60 minutes

### Sensors
- DO meter with mg/L readout
- Temperature probe
- Optional pH meter for later extension

## Controlled Variables
- Water volume
- Initial dissolved oxygen
- Temperature
- Membrane type
- Flow rate
- Gas input rate
- Trial duration

## Test Conditions
### Baseline Condition A
- Static water
- No membrane
- Ambient air only

### Baseline Condition B
- Circulating water
- No membrane interface
- Ambient air input

### Test Condition C
- Circulating water
- Membrane interface installed
- Ambient air input

### Test Condition D
- Circulating water
- Membrane interface installed
- Oxygen-enriched input

## Experimental Procedure
1. Fill chamber with measured water volume.
2. Record initial temperature and dissolved oxygen.
3. Run baseline static trial for defined time.
4. Reset water and repeat with circulation only.
5. Install membrane cassette and repeat trials.
6. Run each condition at least three times.
7. Record DO every 60 seconds for 20–30 minutes.
8. Export results and compare oxygen transfer curves.

## Primary KPIs
- DO increase over time (mg/L)
- Time to reach target DO threshold
- Transfer rate improvement vs baseline
- Repeatability across trials

## Success Gate
Milestone 1 is considered successful if:
- the membrane condition outperforms the strongest baseline,
- the gain is repeatable,
- the setup remains stable without leakage or major sensor drift.

## Documentation Required
- Setup photos
- Wiring/tubing sketch
- Membrane material record
- Calibration sheet
- Raw data table
- Summary graph

## Safety
- No human or animal use
- Pressure kept low
- Gas cylinders handled with regulator and support chain
- Electrical components protected from water contact

## Exit Deliverable
A short technical memo titled:
"Benchtop Oxygen Transfer Validation Report — Milestone 1"
