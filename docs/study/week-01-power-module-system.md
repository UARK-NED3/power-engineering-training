# Week 1 Study Guide: Power Module as a Coupled System

## Core idea

A power module converts or controls electrical energy, but the useful electrical function produces loss that becomes heat. The module, cooling hardware, mechanical attachment, sensors, and test controls therefore form one system.

## Quantities to know

| Quantity | Symbol | SI unit | Meaning |
| --- | --- | --- | --- |
| Voltage | V | V | Electrical potential difference across a defined boundary |
| Current | I | A | Charge flow through a defined path |
| Electrical power | P | W | Instantaneous energy-transfer rate; P = VI only when V and I refer to the same boundary and time |
| Energy | E | J | Time integral of power |
| Average loss | P_loss | W | Electrical power converted inside the selected system boundary to heat and other non-useful outputs |
| Temperature | T | degrees C or K | Temperature at a documented physical location |

A switch can have conduction loss while it carries current and switching loss during changes in voltage or current. The exact loss model depends on the device, operating waveform, temperature, gate drive, and measurement boundary. A student should never insert a generic loss equation into a result without identifying these conditions.

## System map

For a generic half-bridge or comparable module, draw five paths:

1. electrical power entering the module and leaving toward the load;
2. control or gate-drive signals;
3. heat from loss-generating regions through package, interface, cooler, and surrounding environment;
4. mechanical load path through mounting surfaces and fasteners; and
5. measurement path from physical sensor to acquisition system and stored data.

Place the system boundary on the diagram. A reading has meaning only when the sensor location, reference point, and boundary are stated.

## Practice task

With the module de-energized and an owner-approved diagram available, create an original system map. For every label, write one of these evidence classes: observed, owner-provided, assumed, or proposed. Explain why an external case reading does not directly measure junction temperature.

## Self-check

- Can V times I be called module loss without defining input, output, waveform, and averaging window?
- Which path removes heat from the module after loss occurs?
- Which person or document authorizes an energized test?
- What information must remain outside a public repository?
