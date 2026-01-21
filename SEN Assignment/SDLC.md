PROJECT REPORT: SOFTWARE DEVELOPMENT LIFE CYCLE (SDLC)
Project Title: Caleb University Smart Yuletide Rice Distribution & Inventory System

Student Name: DEDE BRIAN KALU
Matric No: 24/15895
Department: Cybersecurity

1. Planning & Requirement Analysis
Objective: To automate the yuletide rice distribution to Caleb University staff.
Goal: Ensure HODs receive correct weights and logistics costs are calculated accurately.
Requirements: Data storage for 8 HODs, search capabilities, and sorting logic.

2. Feasibility Study
Technical: Can be handled with C++ Standard Library and basic algorithms.
Economic: Manages a budget of 3.5 Million Naira, justifying the need for digital tracking.

3. System Design
Architecture: Console-based CLI (Command Line Interface).
Logic: Use of Bubble Sort for organization and Linear Search for data retrieval.

4. Implementation (Coding)
In this phase, the algorithms are converted into C++ code. A key example is the "Bubble Sort Attack" used to organize weights:
// Sample Implementation Snippet
for (int i = 0; i < n - 1; i++) {
    for (int j = 0; j < n - i - 1; j++) {
        if (bags[j] > bags[j + 1]) {
            int temp = bags[j];
            bags[j] = bags[j + 1];
            bags[j + 1] = temp;
        }
    }
}


5. Testing
Validation: Checking that the smallest bag (50kg) always moves to the front of the list.
Safety: Verifying that j < n - i - 1 prevents the program from accessing invalid memory.

6. Deployment & Maintenance
Deployment: Executable files are distributed to the departmental administrative officers.
Maintenance: Updating global constants like logisticCost as transport prices fluctuate annually.
