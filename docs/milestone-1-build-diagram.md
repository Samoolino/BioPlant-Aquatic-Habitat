# Milestone 1 — Build Diagram with Dimensions

## Recommended Bench Footprint
- Table footprint required: **120 cm x 60 cm**
- Recommended working clearance above rig: **50 cm**

## System Dimensions

### A. Main Water Chamber
- Vessel type: clear acrylic or polycarbonate tank
- External dimensions: **40 cm (L) x 25 cm (W) x 25 cm (H)**
- Working liquid volume: **10–15 L**
- Lid: sealed or semi-sealed with ports

### B. Membrane Cassette
- Frame dimensions: **20 cm x 15 cm x 3 cm**
- Effective membrane area target: **150–300 cm²**
- Inlet port diameter: **8–10 mm**
- Outlet port diameter: **8–10 mm**

### C. Pump Module
- Small recirculation pump mounted beside chamber
- Recommended space allocation: **15 cm x 10 cm x 10 cm**
- Flow target: **0.5–5.0 L/min**

### D. Gas Source Module
#### Starter configuration
- Aquarium air pump
- Space allocation: **15 cm x 10 cm x 10 cm**

#### Upgrade configuration
- Oxygen cylinder placed off-bench or floor-mounted with chain support
- Bench connection via tubing only

### E. Sensor Placement
- Dissolved oxygen probe insertion depth: **8–12 cm below water line**
- Temperature probe insertion depth: **10–12 cm below water line**
- Sensor spacing from membrane return zone: **minimum 8 cm**

## Suggested Layout (Top View)

```text
┌──────────────────────────────────────────────────────────────┐
│ [Air / O2 Source] ---> [Membrane Cassette]                 │
│                            ^        |                       │
│                            |        v                       │
│                        [Pump]    Return line               │
│                                        ┌───────────────┐   │
│                                        │ Water Chamber │   │
│                                        │   DO Probe    │   │
│                                        │ Temp Probe    │   │
│                                        └───────────────┘   │
└──────────────────────────────────────────────────────────────┘
Bench: 120 cm × 60 cm
```

## Suggested Layout (Side View)

```text
          Gas line
             |
             v
      ┌───────────────┐
      │   Membrane    │
      │   Cassette    │
      └───────────────┘
          ^       |
          |       v
        Pump    Return

      ┌──────────────────────┐
      │     Water Chamber    │
      │   DO       Temp      │
      │                      │
      └──────────────────────┘
```

## Tubing Lengths
- Pump to membrane inlet: **50–80 cm**
- Membrane outlet to chamber return: **50–80 cm**
- Gas line to membrane: **50–100 cm**

## Port Configuration
- Chamber lid ports: **3 ports minimum**
  1. pump return line
  2. DO probe line
  3. temperature probe or vent

## Assembly Notes
- Keep the membrane cassette slightly above the chamber water line if using leak-sensitive fittings.
- Keep the DO probe away from direct bubble zones.
- Use hose clamps on all pressurized or pump-driven tubing joints.

## Version 1 Build Principle
Use a **rectangular bench rig** rather than a vertical tower or sealed pressure vessel. Simplicity improves repeatability.
