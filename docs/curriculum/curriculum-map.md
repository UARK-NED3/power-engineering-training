# Curriculum Map

## Educational question

How do electrical operating conditions, package construction, and heat-removal paths jointly determine whether a power-electronic component can operate within safe electrical and temperature limits?

The student should answer this question with a clearly bounded model, a traceable data record, and an evidence class for each conclusion.

## Technical conventions

Unless a module states otherwise, use SI units. Electrical power is positive when it enters the selected system boundary. Heat generated inside the package is positive into the thermal network. Temperatures use degrees C for reported differences and K for absolute thermodynamic calculations. Draw the electrical and thermal system boundaries before applying an equation.

## Ten-week sequence

### Week 1 - System context and safe work boundaries

**Question:** What physical paths connect a source, switching device, package, cooling interface, instrumentation, and load?

**Student output:** A block diagram that identifies the electrical power path, control path, heat path, measurement locations, system boundary, and hazards. Mark every element as observed, assumed, or proposed.

**Activity options:** Public-literature orientation; a supervised laboratory walkthrough; or a fictional low-voltage demonstrator diagram. No equipment operation occurs by default.

### Week 2 - Power-electronic quantities and loss mechanisms

**Question:** Which operating quantities create device loss?

**Core quantities:** voltage V in V, current I in A, electrical power P = VI in W, switching frequency f_s in Hz, and energy per event E in J.

**Baseline model:** P_loss = P_cond + P_sw.

Use a device-specific model or a clearly labeled illustrative model for the two terms. Do not treat the relation as a validated loss model without waveform, parameter, and temperature context.

**Check for understanding:** Explain why a lower on-state loss does not necessarily imply lower total loss at a different switching condition.

### Week 3 - Package architecture and interconnection

**Question:** Which package elements carry current, provide insulation, constrain the die, and transfer heat?

**Student output:** An original cross-section sketch of a generic power package. Label functional roles rather than copying a manufacturer's or laboratory drawing.

**Mechanism focus:** A package couples low-resistance current paths, dielectric isolation, mechanical support, environmental protection, and a heat-flow path. Design tradeoffs occur because an interface that helps one function may alter electrical parasitics, thermal resistance, stress, or manufacturability.

### Week 4 - Thermal paths and electronics cooling

**Question:** How does generated heat move from an active region to the ambient environment?

**Baseline model:** T_j = T_ref + P_loss R_theta,j-ref, where T_j and T_ref are temperatures, P_loss is the average dissipated power, and R_theta,j-ref is an aggregate thermal resistance in K/W.

This steady-state relation assumes a defined reference location, an approximately one-dimensional lumped path, and stable boundary conditions. It does not represent transient storage, spreading resistance, or temperature-dependent properties without extension.

**Activity options:** Hand calculation, finite-element or network simulation, or a supervised low-voltage heater experiment using an approved procedure.

### Week 5 - Materials, interfaces, and thermo-mechanical reliability

**Question:** Why can thermal cycling damage an electrically functional package?

**Core idea:** Different coefficients of thermal expansion and constrained geometry create cyclic strain. Interface thickness, stiffness, attachment area, temperature range, dwell time, and manufacturing defects can change local stress and thermal performance.

**Student output:** A cause-and-effect map that distinguishes measured evidence from a proposed failure mechanism.

### Week 6 - Instrumentation and data provenance

**Question:** What does each sensor measure, and what does it fail to measure?

**Student output:** A measurement plan listing sensor type, units, location, sampling basis, calibration status, uncertainty source, and anticipated failure mode. A temperature sensor reports its own sensing location and coupling condition, not an unmeasured junction temperature.

### Week 7 - Electrothermal modeling

**Question:** What minimal model explains a measured temperature trend without overstating accuracy?

**Student output:** A resistor network or transient RC model with a parameter table, assumptions, fit or validation data, residual definition, and valid operating range.

**Minimum checks:** Dimensional consistency; zero-power limit; increasing-temperature response to increased loss for fixed boundary conditions; and comparison against one independent observation when available.

### Week 8 - Experimental planning or simulation alternative

**Question:** What experiment or simulation can separate a proposed mechanism from a competing explanation?

**Student output:** A one-page test plan with objective, controllable factors, response variables, baseline case, safety boundary, instrumentation, repeatability plan, and stop conditions.

**Fallback:** If hardware or authorization is unavailable, execute the same logic through a parameter sweep or literature-derived screening calculation. Label the result as simulated or illustrative.

### Week 9 - Data reduction and uncertainty

**Question:** How much confidence should the observed trend receive?

**Student output:** A reproducible analysis note that preserves raw-data location, preprocessing steps, equations, uncertainty or variability estimate, plot provenance, and limitations. Separate measurement uncertainty, run-to-run variability, numerical error, and model-form error.

### Week 10 - Integrated mini-project

**Question:** What evidence supports one bounded design or research conclusion?

**Student output:** Complete the module cooling-interface capstone specified in module-cooling-interface-capstone.md. The final report and five-minute presentation state the physical problem, system boundary, method, evidence class, results, limitations, and next experiment or model improvement.

## Readiness gates for hardware work

Hardware work requires all of the following before energization:

1. owner-approved procedure and supervisor;
2. completed relevant safety training;
3. reviewed voltage, current, stored-energy, thermal, mechanical, and chemical hazards;
4. written measurement and shutdown plan;
5. confirmed instrument ratings, grounding scheme, and applicable personal protective equipment; and
6. an entry in the student's laboratory notebook.

The curriculum itself does not substitute for any laboratory-specific training or authorization.
