# Optimizing Kidney Paired Donation Using Cycles of 2 and 3 Nodes

**Goal**
<div style="text-align: justify;">
The objective of this project is to develop a graph-based optimization model for Kidney Paired Donation (KPD), aiming to maximize compatible donor-recipient matches within cycles of size 2 and 3. By constructing a directed graph based on compatibility rules, detecting feasible cycles, and formulating an optimization problem, the model ensures that each participant is included in at most one cycle. This approach optimizes kidney exchange programs, streamlining logistical coordination for efficient transplantation planning.
</div>

**Project Overview**
This project uses Python and graph theory to:
- Build a directed graph representing donor-recipient pairs.
- Identify feasible 2-node and 3-node cycles based on predefined compatibility rules.
- Solve an optimization problem to maximize the number of successful exchanges while ensuring fairness.

**Key Features**
- Data Visualization: Displays recipient blood type distribution and cycle structures.
- Optimization Model: Implements algorithms to detect and maximize compatible cycles.
- Results Analysis: Includes detailed statistics on included vs. excluded nodes and donor-recipient pairing success.

**File Contents**
- KDP_project_JRB.ipynb: Jupyter Notebook containing the code, analysis, and visualizations for the project.

**Table of Contents**
1. Introduction: Overview of the problem, goals, and the use of cycles in kidney paired donation.
2. Loading and Analyzing Data: Description of the dataset (JSON format) and its initial analysis, including recipient distribution.
3. Graph Construction: Steps for creating and visualizing the donor-recipient compatibility graph.
4. Cycle Detection: Methods to identify 2-node and 3-node cycles in the graph and their properties.
5. Optimization Model: Mathematical formulation for selecting optimal cycles, including constraints and objectives.
6. Results and Selected Cycles: Summary of the optimization results, including selected 2-node and 3-node cycles.
7. Node Analysis: Identification of nodes included or excluded in the solution, with visualizations of their distribution.
8. Finding Specific Nodes: A function to locate specific nodes and their cycles within the solution.
9. Visualizations: Graphical summaries of the included and excluded nodes by donor and recipient type.
10. Conclusions: Key findings, including insights into the inclusion/exclusion of nodes and cycle optimization.
