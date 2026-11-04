# Module Cooling Interface Capstone

## Purpose

This hands-on capstone tests whether a student can treat an approved power module and its cooler as one coupled electrical, thermal, mechanical, and measurement system. The project does not require module fabrication, disassembly, or a proprietary laboratory procedure. A qualified owner must approve the selected module, station, operating envelope, and written operating procedure before any energized work starts.

## Engineering question

For a fixed, owner-approved electrical operating condition, how does one approved external cooling-boundary condition affect the case-to-reference temperature difference and the inferred external thermal resistance of the module installation?

The project deliberately evaluates the external thermal path. It must not claim a junction temperature or junction-to-case thermal resistance unless the approved test method provides a traceable temperature-sensitive electrical parameter or another valid junction-temperature method.

## Learning evidence

The student demonstrates that they can:

1. identify the electrical loss path, the thermal path, the mechanical contact boundary, and the measurement boundary;
2. predict the direction of the temperature response before collecting data;
3. acquire traceable data using a supervised, approved station;
4. reduce the data with units, uncertainty, repeatability, and an energy-balance check when applicable; and
5. distinguish what the data measured from what the student inferred.

The grade depends on the evidence chain rather than on achieving a particular temperature reduction.

## System boundary and quantities

Draw the selected boundaries before testing. For the recommended external thermal boundary, define:

| Symbol | Meaning | Units | Evidence class |
| --- | --- | --- | --- |
| P_loss | Average electrical loss assigned to the module boundary | W | Measured or derived |
| T_case | Temperature at a documented case measurement location | degrees C | Measured |
| T_ref | Temperature of the selected cooling reference, such as coolant inlet, heat-sink base, or ambient | degrees C | Measured |
| R_theta,case-ref | External thermal resistance, (T_case - T_ref) / P_loss | K/W | Derived |
| m_dot | Coolant mass flow rate, if a liquid loop is used | kg/s | Measured |
| T_in and T_out | Coolant inlet and outlet temperatures, if measured | degrees C | Measured |

Use the actual owner-approved measurement equation for P_loss. If the system boundary permits, the student may calculate P_loss from time-averaged electrical input and output power. If a calorimetric loop is available, the student may calculate Q_dot,coolant = m_dot C_p (T_out - T_in) as an energy-balance check. The cooling-loop calculation does not replace the assigned electrical-loss method unless the owner-approved procedure states otherwise.

## Hypothesis and minimum design

**Hypothesis:** With average module loss, fixture configuration, and reference condition controlled, a cooling condition that lowers the external thermal resistance will lower the steady-state value of T_case - T_ref.

Run one data-rich baseline and one owner-approved contrast condition. The contrast may change only one dominant external condition, for example coolant flow setting, fan condition, or an approved cooler configuration. Do not change internal module construction, electrical connections, or a thermal-interface material unless the owner explicitly approves that comparison.

Use at least three independent runs per condition when station time permits. Repeat the baseline at the end of the session to screen for drift. Randomize or block the condition order when the facility can support it. Independent runs are separate stabilizations or separately defined trials, not multiple samples from a single unchanged record.

## Work packages

### 1. Pre-test prediction and safety review

Before access to the station, submit:

- a system sketch showing electrical, thermal, mechanical, and measurement paths;
- the measurement equation, symbol and unit ledger, and expected response direction;
- a list of confounding mechanisms, including changing loss, sensor coupling, ambient drift, contact pressure, coolant property variation, and incomplete steady state;
- the owner-approved hazard boundary, stop conditions, and division of responsibilities; and
- a statement identifying which conclusions the planned measurements cannot support.

The supervisor approves the plan before any energized work. The student does not energize the module, change connections, or modify the fixture without the supervisor and owner-approved procedure.

### 2. Baseline run

Document the approved station configuration, instrument identifiers, sensor locations, calibration status, sampling basis, and stabilization criterion. Record raw-data location and a run identifier before reducing the data.

For the baseline, show time histories of P_loss, T_case, and T_ref. Justify the analysis window using the observed stabilization behavior and sensor response rather than choosing a window only because it produces a preferred result.

### 3. Contrast run

Change one approved cooling-boundary condition. Keep the electrical operating point and all other controlled conditions within the approved tolerance. Record deviations, aborted runs, and any change in sensor placement or coupling.

### 4. Reduction and evidence check

For each independent run, calculate R_theta,case-ref = (T_case - T_ref) / P_loss with units. Report the number of independent runs, mean, run-to-run standard deviation when justified, and an uncertainty or sensitivity estimate for the derived thermal resistance.

When coolant flow and inlet and outlet temperatures are available, compare Q_dot,coolant with P_loss. Explain any imbalance through system boundary, heat storage, heat loss, sensor uncertainty, timing, or an unresolved cause. Do not force agreement by editing data.

### 5. Technical defense

The student presents the result to the mentor and answers:

1. Which temperature did you directly measure, and which temperature did you infer?
2. Why does the selected cooling condition change or fail to change the observed temperature difference?
3. Which uncertainty source has the greatest effect on the conclusion?
4. What evidence would be required before reporting junction temperature or package reliability?
5. Which next experiment would distinguish contact resistance from a change in electrical loss?

## Required deliverables

1. Completed test plan from templates/module-capstone-test-plan.md
2. Laboratory-notebook entries and a raw-data manifest kept in the approved data location
3. Reproducible calculation worksheet or analysis notebook, with inputs and output version identified
4. One plot of the baseline signals, one condition-comparison plot, and a table of derived thermal resistance
5. Two-page technical memo with an evidence-class label for every key result
6. Five-minute oral defense

## Evaluation rubric

| Criterion | Points | Evidence expected |
| --- | ---: | --- |
| Physical system map and prediction | 20 | Correct boundaries, units, paths, and mechanism-based prediction |
| Safety and experimental planning | 20 | Approved scope, controls, stop conditions, and traceable measurement plan |
| Data quality and provenance | 20 | Complete run record, calibration status, reproducible raw-data location, and documented deviations |
| Analysis and uncertainty | 25 | Correct equations and units, valid analysis window, independent-run treatment, and uncertainty or sensitivity discussion |
| Interpretation and oral defense | 15 | Claims match evidence and limitations; next experiment addresses a remaining ambiguity |

## Pass criteria and limitations

A satisfactory project reports a defensible result even if the contrast condition yields no detectable change. The student must explain whether the result is limited by physics, experimental resolution, inadequate stabilization, confounding variables, or the selected boundary.

The project does not establish a qualified module design, device reliability, safe-operating area, junction temperature, or general cooling correlation. Those claims need additional module-specific evidence and owner approval.

## Non-energized fallback

If the approved station, module procedure, or qualified supervision is unavailable, retain the hands-on portions that do not require energization: inspect the mounting and cooling interface, document sensor placement on a non-energized fixture, construct the measurement model, and perform a controlled data-reduction exercise from an owner-supplied de-identified dataset or a clearly labeled simulated dataset. Mark every result as observed, simulated, or illustrative. This fallback assesses reasoning but does not validate the module under power.
