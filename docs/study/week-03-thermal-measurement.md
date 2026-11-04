# Week 3 Study Guide: Thermal Measurement and Baseline Analysis

## Core idea

A baseline run proves the measurement and analysis chain before comparison cases are interpreted. The student should use the baseline to check signal quality, stabilization, units, sensor placement, data synchronization, and the relationship between assigned loss and measured temperature difference.

## Measurement model

For each run, define the external result:

R_theta,case-ref = (T_case - T_ref) / P_loss

T_case and T_ref are measured temperatures at documented locations. P_loss is measured or derived according to the approved station method. The result is derived, not directly measured.

If a liquid cooling loop has the required sensors and a known fluid heat capacity, a secondary check may be:

Q_dot,coolant = m_dot C_p (T_out - T_in)

Compare Q_dot,coolant and P_loss only after checking that they use compatible time windows and system boundaries. A difference can result from thermal storage, heat loss to other paths, sensor uncertainty, or an incomplete model.

## Baseline review steps

1. Confirm the recorded configuration, instrument identifiers, data location, and calibration status.
2. Plot P_loss, T_case, and T_ref against time.
3. Select an analysis window based on stated stabilization criteria.
4. Compute the temperature difference and external thermal resistance with units.
5. Identify the largest likely uncertainty or sensitivity sources.
6. Preserve excluded and aborted-run records with a reason. Do not delete them to improve an apparent trend.

## Practice task

Using the approved baseline record or an instructor-provided simulated record, produce one plot and one calculation table. State which values are measured and which are derived. Identify one result that the data cannot support.

## Self-check

- Does a steady-looking temperature trace prove that every internal temperature has reached steady state?
- What is the difference between sensor resolution and run-to-run variability?
- Why are multiple samples from the same unchanged time record not independent replicates?
- Which analysis choice could falsely create a difference between conditions?
