
# Clock Multiplier PLL (AI-Assisted SKY130 Design)

## Project Overview

This repository documents my AI-assisted exploration and implementation of a Clock Multiplier Phase-Locked Loop (PLL) using the SKY130 open-source Process Design Kit (PDK) and open-source EDA tools. The project is inspired by the `nitjsr_pll_130nm` reference repository and focuses on understanding, designing, and simulating the fundamental PLL building blocks rather than reproducing the complete design.

The primary objective is to study and verify the operation of the Phase Frequency Detector (PFD), Charge Pump (CP), Loop Filter (LF), Voltage Controlled Oscillator (VCO), and Frequency Divider using AI-assisted workflows and open-source simulation tools.

## Objectives

- Study PLL fundamentals and feedback operation.
- Design and simulate individual PLL circuit blocks.
- Learn the SKY130 analog design flow.
- Perform pre-layout simulations using xschem and ngspice.
- Document AI prompts, generated netlists, simulation results, debugging steps, and observations.
- Build a foundation for future PLL integration and layout design.

## Tools Used

- SKY130 Open PDK
- xschem
- ngspice
- Magic VLSI
- Git & GitHub
- ChatGPT / Codex
mkdir -p week1

cat > week1/README.md << 'EOF'
# Week 1 - Research & Repository Analysis

## Objective
Study the fundamentals of Phase-Locked Loop (PLL) design and analyze the reference SKY130 PLL repository using AI-assisted workflows and to create a single page IEEE format report for this project.

## Tasks Completed
- Studied PLL fundamentals.
- Understood the feedback loop operation.
- Explored the following PLL building blocks:
  - Phase Frequency Detector (PFD)
  - Charge Pump (CP)
  - Loop Filter (LF)
  - Voltage Controlled Oscillator (VCO)
  - Divide-by-8 Frequency Divider
- Analyzed the architecture of the reference repository.
- Learned the purpose of the SKY130 PDK.
- Studied the roles of xschem, ngspice, and Magic.
- Understood the difference between pre-layout and post-layout simulations.
- Learned important PLL concepts:
  - Phase locking
  - Lock time
  - Duty cycle
  - Reference and feedback clock relationship
  - Input/output frequency multiplication (8×)
- Identified common setup issues and debugging strategies.
- Used AI tools to:
  - Summarize the repository
  - Explain PLL concepts
  - Break the project into smaller tasks
  - Plan the implementation workflow

## Outcome
Successfully completed the research phase and prepared for circuit-level implementation beginning with the Phase Frequency Detector (PFD).
- Week 1 Report (Google Drive):https://drive.google.com/file/d/1XBzC7_IfPT1gV5B7gHyh5a-Sf38fwQxt/view?usp=sharing

## Repository Contents

- PLL circuit blocks
- SPICE netlists
- xschem schematics
- Simulation testbenches
- AI prompts and documentation
- Weekly progress and observations

## Reference

This project is based on the open-source `nitjsr_pll_130nm` repository and is intended for educational and research purposes. The work presented here reflects my own understanding and AI-assisted exploration of PLL circuit design.

EOFzAI-assisted exploration and implementation of a Clock Multiplier Phase-Locked Loop (PLL) using the SKY130 open-source Process Design Kit (PDK) and open-source EDA tools. The project is inspired by the `nitjsr_pll_130nm` reference repository and focuses on understanding, designing, and simulating the fundamental PLL building blocks rather than reproducing the complete design.

The primary objective is to study and verify the operation of the Phase Frequency Detector (PFD), Charge Pump (CP), Loop Filter (LF), Voltage Controlled Oscillator (VCO), and Frequency Divider using AI-assisted workflows and open-source simulation tools.

## Objectives

- Study PLL fundamentals and feedback operation.
- Design and simulate individual PLL circuit blocks.
- Learn the SKY130 analog design flow.
- Perform pre-layout simulations using xschem and ngspice.
- Document AI prompts, generated netlists, simulation results, debugging steps, and observations.
- Build a foundation for future PLL integration and layout design.

## Tools Used

- SKY130 Open PDK
- xschem
- ngspice
- Magic VLSI
- Git & GitHub
- ChatGPT 

## Repository Contents

- PLL circuit blocks
- SPICE netlists
- xschem schematics
- Simulation testbenches
- AI prompts and documentation
- Weekly progress and observations

## Reference

This project is based on the open-source `nitjsr_pll_130nm` repository and is intended for educational and research purposes. The work presented here reflects my own understanding and AI-assisted exploration of PLL circuit design.

EOF
