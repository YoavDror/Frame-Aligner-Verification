# Frame Aligner Verification Environment (SystemVerilog)

## Overview
This repository contains a **SystemVerilog-based verification environment** for a **Frame Aligner design**.

The project was developed as a **final project** in a professional **Verification Engineer training program** at  
**Technion – Israel Institute of Technology**.  
The course spanned **six months**, from **May 2024 to November 2024**, and focused on practical verification methodologies and hands-on experience.

During the course, the environment was developed and simulated using **Synopsys VCS**.  
For accessibility and ease of review, the same code can also be executed on **EDA Playground**:
https://www.edaplayground.com/x/KBQL

---

## Project Goals
The primary goal of the project was to:
- Design and implement a **complete verification environment** in SystemVerilog
- Verify the functional correctness of a **Frame Aligner DUT**
- Build tests, run simulations, and collect **functional coverage**

At the beginning of the project, it was explicitly stated that the provided design had already been verified, and that the task would mainly involve building the environment and collecting coverage.

In practice, however, the verification process revealed **three real design bugs**, all of which are documented in detail in: Frame_Aligner_Verification_Project.pdf

---

## Verification Environment
The verification environment includes:
- Transaction-based stimulus generation
- Driver, monitor, and scoreboard components
- Reference model–based checking
- Functional coverage collection and Assertions
- Self-checking tests

The environment was designed without UVM, focusing instead on **clean, structured SystemVerilog verification concepts**.

---

## Key Takeaways from the Course
Through this project and the course, I gained practical experience in:

- Structuring a complete verification environment
- Designing meaningful and targeted test scenarios
- Building and using functional coverage to guide verification
- Debugging real design bugs through simulation
- Writing clear and maintainable SystemVerilog code
- Working with professional simulators such as **Synopsys VCS**
- Managing verification projects over extended timelines

---

## Running the Code
The code can be run in two ways:
1. Using **Synopsys VCS** (as done during the course)
2. Directly on **EDA Playground** using the provided link

The EDA Playground setup includes all required files and configurations to run the simulation.

---

## Author
**Yoav Dror**  
Design Verification Engineer  
B.Sc Electrical Engineering  
