# Power Engineering Training

An interdisciplinary training repository for undergraduate researchers working at the interface of power electronics, electronic packaging, thermal management, measurements, and data analysis.

## Purpose

The curriculum gives a mechanical-engineering student enough electrical and thermal context to reason about a power-electronic system as one coupled physical system. It emphasizes the path from electrical loss generation to heat flow, temperature, mechanical stress, measurement uncertainty, and engineering decisions.

The initial curriculum supports a 10-week UHE-style training period. It can also serve as a modular onboarding sequence when the available laboratory work changes.

## Current status

This repository contains an original curriculum scaffold, source-governance rules, assessment checkpoints, and student-work templates. It does not yet contain laboratory procedures, experimental data, device drawings, or partner-lab assets.

## Training sequence

1. Engineering context, laboratory conduct, and source boundaries
2. Power-electronic operating quantities and loss mechanisms
3. Power-module architecture and electrical interconnection
4. Thermal paths and electronics cooling
5. Materials, interfaces, and thermo-mechanical reliability
6. Instrumentation, calibration, and data provenance
7. First-order electrothermal models
8. Low-risk experimental planning or simulation alternatives
9. Data reduction, uncertainty, and technical communication
10. Integrated mini-project and evidence review

See the curriculum map in docs/curriculum/curriculum-map.md for learning outcomes, governing quantities, and activity options. The module-centered learning test is specified in docs/curriculum/module-cooling-interface-capstone.md.

## Four-week student plan

The four-week study and hands-on sequence in docs/curriculum/four-week-study-and-practice-plan.md combines weekly study guides, supervised module practice, private weekly updates, and an IEEE-ready progress-report path. It is designed to be assigned to an individual student without placing that student's identity, updates, raw data, or partner-lab information in this public repository.

## Source and ownership boundary

The 2025 IEEE EPS UHE materials informed the topic sequence at a high level. This repository must not contain copied text, slides, figures, photographs, diagrams, procedures, tables, screenshots, media, equipment settings, or derivative redrawings from those materials or from partner laboratories.

The repository also excludes student records, applications, resumes, correspondence, grades, identifiers, and contact information. See docs/sources/source-register.md and docs/governance/content-policy.md before adding material.

## Laboratory scope

Training activities use three evidence levels:

- **Desk study or simulation:** public references, hand calculations, and student-authored code. These activities can proceed without laboratory hardware.
- **Low-energy supervised bench work:** activities with an approved written procedure, hazard review, qualified supervision, and recorded instrument configuration.
- **Partner-lab work:** equipment-specific fabrication, assembly, or testing only after the owning laboratory authorizes the activity and contributes or approves a separate procedure.

No repository document authorizes high-voltage, high-current, high-temperature, machining, chemical, vacuum, or assembly work.

## Suggested use

Each learner maintains a notebook from templates/lab-notebook-template.md, completes the checkpoint evidence in docs/curriculum/assessment-plan.md, and develops one bounded mini-project. The mini-project may use a simulated, low-voltage, or approved laboratory system, depending on available resources.

## Repository structure

    docs/
      curriculum/        Original learning plan and assessments
      governance/        Safety, ownership, and contribution rules
      sources/           Provenance and allowed-use register
    templates/            Reusable learner documentation templates
    .github/              Contribution review prompts

## Public release status

This repository is public. No reuse license has been selected yet, so public access does not grant reuse permission. Choose an appropriate license before accepting external contributions or describing the content as openly licensed. The source boundary remains in force after a license is selected.
