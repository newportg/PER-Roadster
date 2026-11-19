# Smart Roadster Coupé electrical conversion options

## Important distinction

There are four different projects behind “electrical conversion”:

1. [Full battery-electric conversion](./smart-roadster-full-ev-conversion.md):
   replace the M160 powertrain with a high-voltage battery and electric drive.
2. **12 V electrical upgrade:** retain the engine and improve reliability,
   grounding, protection, lighting and auxiliary power.
3. **Hybrid/electric assist:** retain the combustion drivetrain while adding an
   electric motor and battery.
4. **Factory-style BRABUS electronics:** retain the M160 and use compatible
   BRABUS ECU, TCU, SAM, immobiliser and instrument components.

They are not interchangeable. An EV conversion does not use a BRABUS ECU/TCU
as its propulsion controller, and a 12 V upgrade does not provide EV traction
power.

## Recommendation for this project

For a road-legal BRABUS Coupé restoration:

- Do the **12 V reliability work** regardless of powertrain choice.
- Build the **factory-style BRABUS electronics** if retaining the M160.
- Treat a **full EV conversion** as a separate engineering and approval project.
- Avoid a DIY hybrid conversion unless a specialist has designed the complete
  mechanical, HV, thermal and approval system.

## 12 V electrical upgrade while retaining the engine

This is the lowest-risk conversion and should be done on any restoration:

- New correctly sized 12 V battery
- Battery isolation switch, if permitted and safely installed
- New positive cable protection and terminal covers
- New engine/chassis/body ground straps
- Voltage-drop test of starter and charging circuits
- Alternator output and ripple test
- Fuse/relay carrier inspection
- SAM connector inspection and water protection
- Additional fused accessory distribution panel
- LED lighting only where approved and compatible
- Modern USB/12 V accessory circuits with dedicated fuses
- Battery maintainer connection
- Optional data logger for voltage and current

Do not increase fuse ratings to cure an overload. Upgrade the cable, connector
and protection as a system.

## Hybrid/electric assist

A hybrid conversion would require all EV components plus:

- Mechanical motor/generator coupling
- Hybrid transmission or motor-in-line adapter
- HV battery and crash enclosure
- Hybrid control unit
- Engine torque coordination
- Regenerative brake blending
- Cooling for motor, inverter, battery and engine
- HV isolation from the original 12 V system
- New torque-reaction and structural mounts

The 452 has limited packaging space and an unusual rear-mid powertrain. A
hybrid system is substantially harder than a pure EV conversion because both
powertrains must remain safe and coordinated. It is not a practical first
conversion for a road-legal restoration.

## Factory-style BRABUS electronics

For an engine-powered BRABUS Coupé, retain the original vehicle architecture:

- BRABUS-compatible engine calibration/ECU
- Compatible engine harness
- Correct TCU and actuator calibration
- Original or matched SAM
- ABS/ESP module compatible with the brake/wheel configuration
- Original immobiliser, key and security pairing
- Instrument cluster and warning strategy
- Original CAN network and diagnostic connector
- BRABUS engine/exhaust/suspension hardware as applicable

This is a compatibility and restoration task, not a new electrical architecture.
The donor's matched modules should be preserved together. Do not mix unknown
ECU, SAM, TCU and keys without a documented coding plan.

## Comparison

| Track | Retains M160? | HV system? | Main difficulty | Suitable first project? |
|---|---:|---:|---|---:|
| 12 V upgrade | Yes | No | Wiring quality and water prevention | Yes |
| Factory BRABUS electronics | Yes | No | Module compatibility and coding | Yes, with matched donor |
| Full EV conversion | No | Yes | Packaging, HV safety and approval | Only with specialist support |
| Hybrid assist | Yes | Yes | Two coordinated powertrains | Generally no |

## Related documents

- [Full-EV conversion](./smart-roadster-full-ev-conversion.md)
- [BRABUS Coupé build BOM](./smart-roadster-brabus-coupe-build-bom.md)
- [Electrical test-bed procedure](./smart-roadster-452-electrical-test-bed.md)
- [Documentation index](./README.md)

## Safety and legality

High-voltage work requires trained personnel, insulated tools, lockout/tagout,
verified absence-of-voltage procedures and appropriate emergency controls.
EV or hybrid conversions may require approval, updated registration, electrical
safety evidence, braking validation, weight/axle-load verification and
insurance disclosure. Requirements vary by country.
