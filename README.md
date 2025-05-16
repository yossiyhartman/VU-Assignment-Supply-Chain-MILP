# Optimal Customer Delivery Plan – Supply Chain Lab (VU Amsterdam)
This repository contains my project for the Supply Chain Lab course at Vrije Universiteit Amsterdam. The goal? To design an optimal delivery plan using Mixed Integer Linear Programming (MILP) and tackle one of the classic challenges in logistics: getting goods to customers as efficiently as possible.

#### Project Overview
The project is built around a case study focused on optimizing customer delivery routes. It’s split into four parts, each solving a specific subproblem—but the main focus here is on the third part: solving the Vehicle Routing Problem using MILP.

#### Includes
- **Mixed Integer Linear Programming (MILP)**: MILP is used to model and solve the VRP, ensuring all constraints (like delivery demand and vehicle capacity) are respected.
- **Route Optimization**: The model minimizes the total distance traveled while meeting all customer requirements.
- **Scalable Design**: The solution can handle different problem sizes, adjusting to various numbers of customers and vehicles.
- **Sensitivity Analysis**: Includes an exploration of how small changes in parameters (e.g. demand or vehicle limits) impact the solution’s effectiveness and feasibility.
