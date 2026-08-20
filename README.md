In this project we will be using a basic IP model and solve its variables in various ways: 
Branch And Bound, Sensitivity Analysis, Knapsack, and Solver. 
The following group members are:
Karabo Masoka, Regoratile Mokoene, Ulrich Rossouw, Mkhanyisi Mqadi and Aphelele Mdebuka
Team Task Allocation:

Member 1: Architecture, Parser & Output File Manager
Responsibility:
Build the text file parser (LinearProgramParser.cs) handling max/min, operators (+/-), coefficients, constraints (=, <=, >=), and sign restrictions (urs, bin, int, +, -).
Build the Canonical Form transformer.
Build OutputFormatter.cs to write formatted output text files with numbers rounded to 3 decimal places.
Build the CLI Menu system for solve.exe.

Member 2: Primal & Revised Simplex Engine
Responsibility:
Implement the standard Primal Simplex Algorithm (tableau generation, pivot selection, ratio test, step-by-step output).
Implement the Revised Primal Simplex Algorithm (Product Form of Inverse B^-1, Price-Out Vectors, non-tableau iterations)
Handle special cases: Unbounded and Infeasible solution detection.

Member 3: Branch & Bound Specialist (Simplex & Knapsack)
Responsibility:
Implement Branch & Bound Simplex Algorithm: Sub-problem creation, Node fathoming (infeasible, integer optimal, bounded), Backtracking traversal tree.
Implement Branch & Bound Knapsack Algorithm specifically optimized for 0–1 Binary Integer Knapsack problems.

Member 4: Cutting Plane Algorithm & Duality
Responsibility:
Implement the Cutting Plane Algorithm (generating Gomory cuts from fractional tableau rows and re-optimizing).
Build the Duality Engine: Automatically generate the Dual problem, solve it, and verify Strong/Weak duality.

Member 5: Sensitivity Analysis Engine & Video Lead
Responsibility:
Implement Sensitivity Analysis operations:
- Range of Basic & Non-Basic variables.
- Range of RHS values (bi)
- Applying changes to Basic/Non-Basic variables & RHS values.
- Adding a new activity (variable column) or constraint to an optimal tableau.
- Shadow price calculation.
Video Recording & Editing: Script, record, edit, and host the final demo video demonstrating all rubrics.
