# analog-integrated-circuit-design
This file contains information about my project 2-stage Op-amp

📌 Project Overview
  Objective: Design a high-gain, stable two-stage op-amp for analog signal processing applications using a 0.4μm CMOS process.

  Methodology: Using Cadence Virtuoso and NCSU_TechLib_TSMC04_4M_2P, the op-amp was designed, biased, and simulated. The design was analyzed for open-loop gain, phase margin, output swing, and CMRR.

💡 Key Features
  High-gain two-stage architecture optimized for 3.2V single supply

  Bias current and compensation capacitor tuned for >50° phase margin

  Achieved DC gain: 2756.25 V/V

  Load capacitance (CL): 5pF, Phase Margin: 53°, Slew Rate verified

  Gain-bandwidth product (GBW) and stability margins verified

🧰 Skills Used
   Analog Circuit Design

  Frequency Compensation

  Biasing and Current Mirror Design

  Op-Amp Simulation and Analysis

  Gain & Phase Margin Tuning

🧪 Technologies & Tools
   Cadence Virtuoso

  NCSU_TechLib_TSMC04_4M_2P PDK

  Simulation Analyzers (AC/DC/Transient Sweep)

  Plot viewer for waveform and gain-phase response

🔍 Key Findings
  Two-stage op-amp achieved a gain of 2756.25 V/V with a clean phase margin of 53°

  Layout-aware constraints like power, area, and compensation trade-offs significantly affect stability

  The use of Miller compensation allowed flexibility across varying load conditions

🎓 What I Learned
  The importance of bias point selection in gain and output swing

  Phase margin tuning through compensation capacitors and sizing
  
  Real-world challenges in CMOS analog design including trade-offs between gain, speed, and stability

🚀 Future Work
  Layout extraction using DRC and LVS

  Corner and Monte Carlo analysis for mismatch and PVT robustness

  Extension into folded cascode architecture or telescopic OTA variants for better performance

📂 Files Attached
  opamp_schematic.dsn – Op-Amp schematic in Cadence Virtuoso

  opamp_gain_phase.raw – AC sweep simulation plots

  opamp_transient.raw – Time-domain transient test results

README.pdf – Documentation and design explanation report
