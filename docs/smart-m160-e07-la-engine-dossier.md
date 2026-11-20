# Mercedes-Benz / smart M160 E07 LA engine dossier

## Scope and evidence status

This note gathers public technical information for the **M160 E07 LA**, with
particular attention to its use in the smart Roadster / Roadster Coupé (W452).
It is a research reference, not a workshop manual. The E07 LA designation covers
multiple output calibrations, so a displacement or engine-family match does not
prove that a component, ECU map or service value fits a particular vehicle.

The strongest publicly accessible data found for this summary is the
engine-family table reproduced by the [M160 reference](https://en.wikipedia.org/wiki/Mercedes-Benz_M160_engine),
cross-checked against the [Parkers 80 bhp Roadster Coupé specification](https://www.parkers.co.uk/smart/roadster/coupe-2003/(80bhp)-2d-auto-(lhd)/specs/)
and the [452 manual index](https://smartcarmanuals.com/models/452-roadster/).
The first is a secondary source and the latter two are catalogue/community
references; exact repair work still requires VIN-matched Mercedes/smart WIS,
EPC and diagnostic data.

## Engine identity

| Item | Public technical baseline | Confidence / qualification |
|---|---|---|
| Manufacturer family | Mercedes-Benz M160, also branded Suprex | Medium; family reference |
| Variant designation | M160 E07 LA | Medium; public family/model references |
| Configuration | Inline three-cylinder petrol | Medium/high |
| Displacement | 698 cc (0.7 L) | Medium/high |
| Bore x stroke | 66.5 mm x 67.0 mm | Medium; engine-family reference |
| Cylinder head / valve train | SOHC, two valves per cylinder; six valves total | Medium |
| Compression ratio | 9.5:1 | Medium; engine-family reference |
| Induction | Single turbocharger | Medium/high |
| Turbocharger identified in family reference | Garrett GT12 | Medium; confirm from the turbo ID plate |
| Fuel system | Fuel injection | Medium/high; exact injector and pressure data are variant-specific |
| Cooling | Water-cooled | High at family level |
| Emissions hardware | Three-way catalytic converter | Medium; market/emissions package can differ |
| Published engine mass | About 59 kg | Medium; mounting/ancillary scope is not defined |

The 0.7 L E07 is the enlarged successor to the 599 cc E06 family. It should
not be assumed that an E06 and E07 long engine, ECU calibration, wiring or
ancillary set are interchangeable.

## Output variants

The following figures are the public E07 LA family table. They show why the
engine code alone is insufficient to identify the installed tune.

| Public output | Power | Torque | Published peak-speed information | Application context |
|---|---:|---:|---|---|
| Low output | 37 kW / 50 PS / 50 hp | 80 Nm | 5,250 rpm power; 1,800 rpm torque | 450-era E07 application; not the normal W452 Roadster tune |
| Standard Roadster-family output | 46 kW / 63 PS / 62 hp | 95 Nm | 5,250 rpm power; 2,000–4,000 rpm torque | Publicly listed for the 2003–2006 E07 family |
| Higher-output Roadster | 61 kW / 83 PS / 82 hp | 110 Nm | 5,250 rpm power; 2,250–4,500 rpm torque | Common W452 standard/high-output calibration |
| BRABUS Roadster | 74 kW / 101 PS / 99 hp | 130 Nm | 5,250 rpm power; 2,500–5,300 rpm torque | Factory BRABUS calibration, hardware and trim context |

Catalogue naming can make the 61 kW version appear as either “80 bhp” or
“82 hp/PS” depending on the market and unit convention. Parkers lists the
Roadster Coupé version as 80 bhp, 110 Nm and 698 cc, with a six-speed
transmission. Treat the kW value and the vehicle data card/ECU identity as the
more useful cross-checks.

Do not treat the 74 kW BRABUS numbers as a specification for every E07 LA
engine. A factory BRABUS identification should be supported by the vehicle
data card, ECU/calibration evidence, turbo/fuelling/exhaust hardware and VIN
matched parts information.

## W452 installation and connected systems

In the W452 the engine is mounted between the seats and the rear axle, driving
the rear wheels through a six-speed automated manual transmission. The
transmission is a conventional manual gearset with an automated single-clutch
system, not a torque-converter automatic or dual-clutch gearbox.

The engine-related control chain includes:

- engine ECU and engine wiring harness;
- crank, cam, temperature, intake pressure/temperature and oxygen sensing;
- throttle, injectors and ignition coils;
- turbocharger, wastegate actuator, charge-air plumbing and intercooler;
- exhaust manifold, catalyst and heat shielding;
- fuel delivery, evaporative-emissions plumbing and fuel pressure control;
- CAN communication with the transmission controller for torque reduction and
  shift coordination.

The radiator is at the front of the car while the engine is at the rear.
Consequently, coolant pipes under the vehicle and the full front-to-rear
cooling circuit are part of the engine system, not incidental body plumbing.

## Service and inspection information available publicly

The [public 452 fluid reference](https://smartcarmanuals.com/maintenance/fluids-spec-table/)
lists the following as planning values:

| Item | Public planning value | Important limitation |
|---|---|---|
| Engine oil | 5W-40, ACEA A3/B4; approximately 3.0 L with filter | Fill by dipstick/approved procedure; confirm the exact workshop specification |
| Coolant | Approximately 4–5 L for the 450/451/452 family | The circuit must be bled correctly; capacity varies with drain/refill method |
| Fuel | Premium unleaded is commonly specified for the 452 | Confirm the market owner's/manual data and any modification requirements |

These are not substitutes for a service manual. The public sources located for
this research do **not** reliably establish one exact value for all E07 LA
variants for:

- fastener torque settings;
- valve clearances;
- ignition timing or knock-control limits;
- injector flow, fuel pressure or ECU pin assignments;
- normal boost pressure or wastegate adjustment;
- turbo oil-feed/return service limits;
- compression-test acceptance limits;
- timing-drive replacement procedure;
- complete engine-removal, bleeding or adaptation procedures.

Those values should be taken from the applicable WIS/repair information and
the car's engine/ECU identification, not from a generic E07 listing.

## Sensible diagnostic record for a particular engine

Before buying parts or changing calibration, record:

1. VIN, data card and build date;
2. engine number/stamping and ECU hardware/software identification;
3. turbocharger identification plate and wastegate arrangement;
4. injector and ignition-coil markings;
5. catalyst/emissions label and market;
6. stored ECU, TCU, ABS/ESP, SAM and SRS fault codes;
7. battery voltage during cranking and actuator operation;
8. cold-start behaviour, smoke, oil pressure evidence and coolant behaviour;
9. charge-air hoses, intercooler, vacuum/pressure lines and wastegate movement;
10. front-to-rear coolant pipes, expansion tank, thermostat, radiator and fan;
11. oil leaks, crankcase-breather routing and evidence of overheating;
12. clutch adaptation values and shift faults before replacing transmission parts.

An adaptation reset can only relearn control values. It cannot repair a worn
clutch, failed actuator, low battery voltage, boost leak, mechanical selector
fault or engine problem.

## What is confirmed versus still open

### Reasonably established at family level

- 698 cc, inline three-cylinder, turbocharged petrol architecture.
- 66.5 mm bore, 67 mm stroke and 9.5:1 published compression ratio.
- SOHC, two valves per cylinder, water cooling and fuel injection.
- E07 output range published from 37 kW to 74 kW, with 46/61 kW relevant to
  ordinary Roadster applications and 74 kW associated with BRABUS Roadsters.
- Rear-mid W452 installation with a six-speed automated single-clutch gearbox.

### Requires vehicle-specific confirmation

- Exact output calibration and whether the car is standard, high-output,
  BRABUS or modified.
- ECU, turbo, injectors, exhaust, intercooler and emissions revisions.
- Engine number, software version, coding and immobiliser pairing.
- Service limits, torque settings, fluid fill procedure and diagnostic tests.
- Whether a replacement long engine is complete, bare, or supplied with the
  correct W452 ancillaries and mounts.

## Source notes

1. [Mercedes-Benz M160 engine](https://en.wikipedia.org/wiki/Mercedes-Benz_M160_engine) —
   secondary engine-family architecture, dimensions, compression, turbo and
   output table.
2. [Parkers Smart Roadster Coupé 80 bhp LHD specification](https://www.parkers.co.uk/smart/roadster/coupe-2003/(80bhp)-2d-auto-(lhd)/specs/) —
   catalogue confirmation of the 698 cc, 3-cylinder, 110 Nm W452 variant and
   its 61 kW-class performance.
3. [smart 452 roadster manual index](https://smartcarmanuals.com/models/452-roadster/) —
   public model/variant orientation and links to workshop/manual material.
4. [smart fluids and specifications quick reference](https://smartcarmanuals.com/maintenance/fluids-spec-table/) —
   approximate oil/coolant planning values, explicitly requiring workshop
   manual verification.

