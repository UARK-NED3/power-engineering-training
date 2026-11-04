# Four Week Study and Module Practice Plan

## Purpose and delivery model

This four-week sequence prepares one early-career mechanical-engineering student to describe and evaluate an approved power module as a coupled electrical, thermal, and mechanical system. Each week combines directed study, an original student artifact, supervised practice with the module or station, and a short private update to the faculty mentor.

This public repository contains the learning materials and templates. Weekly updates, raw data, photographs of partner equipment, owner-approved procedures, and student-identifying information must be submitted through the approved private channel rather than committed here.

## Weekly cadence

At the end of each week, the student submits a one-page update using templates/weekly-update-template.md. The update states completed study, activity performed, evidence produced, questions, safety issues, and the next week's plan. The mentor reviews the update before authorizing the next week's hands-on task.

The final report is due on the IEEE EPS schedule confirmed by the faculty sponsor. Start the report in Week 2 so that December becomes an editing and submission period rather than a writing-only period.

## Week 1 - Power-module system map and safe observation

**Learning question:** How do electrical power, control signals, heat flow, mechanical interfaces, and measurements connect in a power-module test system?

**Study packet:**

- docs/study/week-01-power-module-system.md
- Public study sources in docs/sources/public-study-resources.md
- The owner-approved module datasheet and station drawing, reviewed only through the approved private channel

**Study outcomes:**

- Define voltage, current, electrical power, energy, and average loss with units.
- Distinguish the electrical power path from the control or gate-drive path.
- Explain why a module can have a safe external case temperature while an internal junction temperature remains unknown.
- Identify who authorizes module operation and what information is not suitable for a public repository.

**Hands-on practice:** With a qualified supervisor and with the module unenergized, map the externally accessible module, cooling interface, sensors, and test-station subsystems. Use only terminal names and locations confirmed by the owner. Do not remove covers, loosen fasteners, make connections, or infer internal layout.

**Student artifact:** Original system map showing the electrical, thermal, mechanical, measurement, and safety boundaries. Mark each item as directly observed, owner-provided, assumed, or proposed.

**Weekly update evidence:** System map, three study notes, one unresolved technical question, and a signed statement that no module operation occurred.

## Week 2 - Packaging functions and cooling-interface preparation

**Learning question:** Which package and installation features carry current, provide isolation, constrain components, and transmit heat to the cooling boundary?

**Study packet:**

- docs/study/week-02-packaging-and-interfaces.md
- docs/curriculum/module-cooling-interface-capstone.md, sections on system boundary and hypothesis
- The owner-approved mounting and instrumentation instructions, reviewed privately

**Study outcomes:**

- Describe the distinct functions of electrical interconnects, dielectric isolation, structural support, environmental protection, and thermal interfaces.
- Relate a temperature difference to a thermal resistance only after defining the two temperature locations and the heat-rate boundary.
- Explain why mounting force, surface condition, sensor attachment, and cooling reference can change the measured result.

**Hands-on practice:** Under direct supervision, inspect the approved mounting and cooling fixture. The student documents sensor locations, cooling reference, fixture identifiers, and the allowed configuration states. If the owner authorizes it, the student may perform a prescribed non-energized assembly or instrumentation check using the owner-specified method. Do not record proprietary settings or images in the public repository.

**Student artifact:** A measurement plan with a labelled generic cross-section, a sensor-location table, the proposed external thermal-resistance equation, and a list of confounders.

**Weekly update evidence:** Measurement plan, updated report outline, readiness status, and any item requiring owner or mentor resolution.

## Week 3 - Baseline electrothermal observation

**Learning question:** What does the baseline condition measure, and what does it leave unresolved?

**Study packet:**

- docs/study/week-03-thermal-measurement.md
- The approved capstone test plan in templates/module-capstone-test-plan.md
- The station-specific operating procedure, reviewed privately

**Study outcomes:**

- Calculate the external thermal resistance R_theta,case-ref = (T_case - T_ref) / P_loss with consistent units.
- Distinguish a directly measured case or coolant temperature from a calculated or inferred temperature.
- Select an analysis window using stabilization and sensor-response evidence.
- Identify calibration, resolution, repeatability, drift, and system-boundary effects that affect the result.

**Hands-on practice:** Perform or observe one owner-approved baseline run at the approved station. The supervisor controls energization and any configuration change. The student records the approved run identifier, raw-data location, instrument status, start and stop observations, and deviations in the private notebook.

**Student artifact:** One baseline time-history plot of the approved signals, a completed notebook entry, and a preliminary calculation table. Mark the result as measured, derived, or inferred.

**Weekly update evidence:** Baseline plot, data-manifest entry, preliminary calculation with units, and an uncertainty or sensitivity list.

## Week 4 - Controlled cooling contrast and technical interpretation

**Learning question:** Does one approved change in the external cooling boundary produce the predicted change in the measured external thermal response?

**Study packet:**

- docs/study/week-04-data-interpretation-and-reporting.md
- docs/curriculum/module-cooling-interface-capstone.md, sections on contrast run, reduction, and technical defense
- docs/curriculum/ieee-progress-report-guide.md

**Study outcomes:**

- Compare a baseline and one contrast condition without conflating different electrical losses, mounting changes, or ambient conditions.
- Report independent-run count, variability, and uncertainty or sensitivity range.
- Explain a null result as a possible physical, measurement, or design outcome rather than a failed exercise.
- Write a bounded conclusion and identify the next experiment that would reduce uncertainty.

**Hands-on practice:** Conduct or observe one owner-approved cooling-boundary contrast. Repeat the baseline when practical to screen for drift. The student completes reduction, compares conditions, and presents an oral defense to the mentor.

**Student artifact:** One comparison plot, a thermal-resistance summary table, a two-page report draft, and a five-minute oral briefing.

**Weekly update evidence:** Comparison result, report draft status, open limitations, and the exact items needed for IEEE submission.

## Progression rule

The plan advances only when the previous weekly update shows safe, traceable completion. If the station, procedure, or supervision is unavailable, replace the live task with the non-energized or simulated fallback defined in the capstone. The student must label that work accordingly and must not report it as module-under-power evidence.
