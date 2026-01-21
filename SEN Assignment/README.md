Caleb University: Yuletide Rice Distribution & Inventory System
Department of Cybersecurity | COS201 & SEN Project

 Student Information
Name: DEDE BRIAN KALU
Matric No: 24/15895
Department: Cybersecurity
Institution: Caleb University

Project Description
This project implements a secure and efficient logic for managing the distribution of yuletide rice to Departmental HODs. It solves the real-world problem of inventory tracking, algorithmic sorting of weights, and financial auditing of logistics expenses.

 Software Engineering Methodology
This project followed the Waterfall SDLC Model. This linear-sequential life cycle was chosen because the requirements (the list of HODs and fixed logistics costs) were well-defined and unlikely to change during the development process.

Key Algorithmic Components:
Search Logic: Linear Search used for departmental data retrieval.
Sort Logic: "Bubble Sort Attack" for organizing bag weights in ascending magnitude.
Financial Logic: Fixed-point arithmetic for Naira (NGN) currency calculations.

Documentation Structure
SDLC_Infographic.html: Visual representation of the development lifecycle.
main_system.cpp: The source code implementation.
SDLC_Report.pdf: Comprehensive breakdown of each phase.

 Cybersecurity Considerations
As a Cybersecurity student, the implementation prioritizes:
Input Validation: Ensuring search queries do not cause buffer overflows.
Data Integrity: Preventing logic errors during the swap phase of sorting by using temporary memory buffers.
Boundary Protection: Implementing n-1 guardrails to prevent memory access violations (out-of-bounds errors).

