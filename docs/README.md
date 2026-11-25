# Smart Roadster 452 documentation stack

This stack is a public-source engineering and restoration reference for the
Smart Roadster / Roadster Coupé W452. It is organized to keep confirmed facts,
catalogue values, owner experience and VIN-dependent data separate.

## Documents

| Document | Purpose |
|---|---|
| [Reference dossier](./smart-roadster-452-reference-dossier.md) | Consolidated specifications, architecture, parts taxonomy, diagrams, inspection worksheet and evidence limits |
| [M160 E07 LA engine dossier](./smart-m160-e07-la-engine-dossier.md) | Engine architecture, output variants, W452 integration, public service values and evidence limits |
| [M160 engine-running stand](./smart-m160-engine-running-stand.md) | Preliminary unloaded stand concept, system diagrams and engineering/commissioning requirements |
| [M160 running-stand 3D concept](./assets/m160-running-stand-3d.html) | Interactive, illustrative model; geometry and mount locations are not verified |
| [Source and evidence register](./smart-roadster-452-source-register.md) | What each public source contributes, confidence, and what still requires primary documentation |
| [Master parts catalog](./smart-roadster-452-master-parts-catalog.md) | All major 452 part families with variant scope, OEM/supersession/cross-reference fields and verification workflow |
| [BRABUS Coupé build BOM](./smart-roadster-brabus-coupe-build-bom.md) | Donor-car acquisition checklist and factory-style BRABUS Coupé build inventory |
| [Schematics and image index](./smart-roadster-452-schematics-image-index.md) | Direct links to 452 electrical schematics, fuse diagrams, body/roof images, chassis figures and source indexes |
| [Electrical test-bed procedure](./smart-roadster-452-electrical-test-bed.md) | Staged, current-limited donor-harness test approach for modules, CAN and safe loads |
| [Electrical conversion options](./smart-roadster-electrical-conversion-options.md) | Comparison of EV, 12 V, hybrid and factory-BRABUS electrical approaches |
| [Full-EV conversion](./smart-roadster-full-ev-conversion.md) | Detailed EV architecture, parts, configuration, sizing, performance and testing |

## Recommended working order

1. Establish the exact VIN, build date, market, body style and calibration.
2. Use the reference dossier for system orientation and terminology.
3. Use the source register to decide whether a value is safe for planning or
   requires workshop-manual confirmation.
4. Add vehicle-specific measurements, photographs, scan reports and invoices.
5. Promote a value to “confirmed” only when the source and vehicle agree.

## Safety and copyright boundary

This is not a substitute for official repair information. Do not use a
summary as authority for structural repair, airbag/SRS work, braking systems,
high-voltage testing, ECU coding, torque settings or roadworthiness approval.

The stack links to manuals and diagrams but does not reproduce complete
copyrighted workshop-manual pages, proprietary wiring pinouts or repair
procedures. Those should be consulted from a lawfully obtained copy.

## Missing information for a complete strip-down and rebuild

**The current documentation is not sufficient to dismantle and reassemble a
complete car.** The [master parts catalog](./smart-roadster-452-master-parts-catalog.md)
is a starting inventory, not a complete VIN-verified parts list: many part
numbers and supersessions are pending, and some descriptions, quantities and
fitment assumptions still need checking against the actual car.

The checklist below identifies information **not yet recorded or verified in
this project**. It does not mean that no external source exists. Public
manuals and diagrams are indexed in the
[source register](./smart-roadster-452-source-register.md), but their coverage,
provenance and applicability have not all been verified. Factory systems may
require a subscription, a dealer or a specialist workshop. Obtain documents
lawfully and check them against the specific vehicle.

### Vehicle identity and baseline

- [ ] VIN-matched data card, build date, market, body style, steering side,
  option codes and confirmation of standard or BRABUS specification.
- [ ] Engine and gearbox numbers; ECU, transmission control, SAM, ABS/ESP,
  SRS, cluster and key identities and software/coding records.
- [ ] Pre-disassembly condition record: photographs, corrosion and damage,
  panel gaps, leaks, operating faults, diagnostic scans and measurements.
- [ ] Vehicle-specific record of modifications, missing parts, previous
  repairs and parts that do not match the data card.

Keep vehicle identity, key/security details and diagnostic records securely;
do not publish sensitive vehicle or security data in a public repository.

### Complete parts inventory

- [ ] VIN-filtered factory parts catalogue and exploded diagrams, including
  part numbers, supersessions, quantities, left/right position and option
  applicability. Record the source revision and check against installed parts.
- [ ] Engine internals and ancillaries: block, head, timing and valve gear,
  pistons, bearings, lubrication, ignition, sensors, brackets, mounts,
  gaskets, seals and fasteners.
- [ ] Turbo, intake, intercooler, exhaust and emissions equipment, including
  pipes, hoses, shields, clamps, brackets, gaskets and their routing.
- [ ] Fuel tank, pump, sender, filler, lines, filters, injectors, evaporative
  system and all connections and mounting hardware.
- [ ] Cooling and heating system, including radiator, fans, expansion tank,
  water pump, thermostat, front-to-rear pipes, heater, hoses and clips.
- [ ] Gearbox, differential, clutch, flywheel, starter interface, actuators,
  selector, driveshafts, joints, seals, mounts and related hardware.
- [ ] Front and rear suspension, subframes, steering, hubs, bearings, wheels
  and tyres, including bushes, spacers, adjusters and fasteners.
- [ ] Brake and parking-brake assemblies, hydraulic pipes and hoses, ABS/ESP
  components, sensors and mounting hardware; verify the installed brake
  configuration rather than assuming it from a generic catalogue.
- [ ] Tridion structure, panels, bumpers, glazing, doors, locks, mirrors,
  roof, seals, drains, trim, clips and body-specific fittings.
- [ ] Wiring harnesses, connectors, terminals, grounds, fuses, relays,
  sensors, switches, control units, lamps and all option-specific equipment.
- [ ] Seats, belts, airbags, pretensioners, SRS components, dashboard,
  instruments, interior, heating/ventilation and optional air conditioning.
- [ ] Consumables and small parts: single-use bolts and nuts, washers,
  retaining clips, seals, sealants, adhesives, lubricants and corrosion
  protection, with approved specifications and quantities.

For each item, record its location, quantity, orientation, condition, removal
photos, original and replacement number, fitment evidence, reuse decision,
storage label and any linked assembly procedure. The existing parts catalogue
needs expansion and verification before it can meet this requirement.

### Torque settings, adjustments and specifications

- [ ] A VIN- and revision-matched fastener schedule for **every disturbed
  joint**, covering engine internals and ancillaries; turbo/exhaust; gearbox,
  clutch and driveshafts; engine and subframe mounts; suspension, steering,
  hubs and wheels; brakes; body, seats, belts and restraint-system fixings.
- [ ] For each fastener: location and identification, thread/grade, torque,
  tightening angle and sequence where specified, number of stages, applicable
  dry/lubricated/threadlocked condition, required replacement and the source.
  Record special conditions such as tightening suspension at the specified
  ride height where the applicable procedure requires it.
- [ ] Engine and gearbox inspection limits, clearances, wear measurements,
  gasket/sealant specifications, timing and alignment procedures, and
  replacement criteria.
- [ ] Suspension alignment settings and measurement conditions; brake,
  steering, wheel and tyre specifications; panel, door, window, roof and seal
  adjustment values.
- [ ] Approved fluids and refrigerant: specification, capacity, fill points,
  filling/bleeding procedure and disposal requirements for each actual system.
  Existing approximate planning values are not a rebuild specification.

Do not substitute a generic torque table for a vehicle-specific instruction or
infer a reuse decision from appearance. The project currently has **no
complete, verified torque schedule**.

### Procedures, tools and completion checks

- [ ] Vehicle-specific removal, installation and assembly sequences,
  orientation diagrams, lifting/support points and special precautions for
  each system, including the complete engine/gearbox and body/roof.
- [ ] Factory structural dimensions and approved inspection/repair procedures
  for the safety cell, mounting points and corrosion or collision damage.
- [ ] Complete applicable wiring diagrams, connector and ground locations,
  pinouts, harness routing, fuse/relay assignments and connector repair data.
- [ ] SRS isolation, handling and reinstatement information; air-conditioning
  refrigerant recovery and service procedures; specialist work and equipment
  required for safety-critical systems.
- [ ] Special tools, lifting equipment, measuring instruments, diagnostic
  interfaces and their calibration or inspection requirements.
- [ ] Diagnostic tests, module coding/security pairing and clutch/gear
  adaptation procedures supported by the actual car and diagnostic tool.
- [ ] Post-assembly inspection and acceptance criteria: fluid and leak
  checks, electrical and fault-code checks, cooling and fan operation, brake
  and steering checks, alignment, lights, restraint-system diagnostics,
  emissions and applicable roadworthiness requirements.
- [ ] A staged work plan and signed records connecting each removed part and
  fastener to its installation, specification, inspection and test result.

### Sources and access to arrange

- [ ] Lawfully obtained, applicable Mercedes/smart WIS/ASRA workshop
  instructions and specifications, including the correct revision.
- [ ] VIN-driven Mercedes/smart EPC or dealer parts information and
  supersession records, including illustrations for all fitted options.
- [ ] Applicable electrical diagrams and connector information; compare
  public sources with the vehicle and factory revision.
- [ ] Access to a suitable XENTRY/DAS or equivalent qualified Smart diagnostic
  service for the required module tests, coding and adaptations.
- [ ] Access to qualified specialists for structural, SRS, refrigerant,
  calibration and other work outside the available equipment or competence.

**Reassembly gate:** do not dismantle a safety-critical assembly until its
correct procedure, replacement parts, specifications, tools and verification
method are available. Do not return the car to the road until all applicable
inspections and legal requirements are satisfied.
