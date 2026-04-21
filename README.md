# Vehicle Route Optimization (VRP)

**Optimizing delivery/pickup routes for a fleet of vehicles in Hyderabad** — Real-world Operations Research project for Yulu fleet operations.



---

##  Problem Statement
Given a set of pickup and drop locations, find the **most optimal routes** for multiple vehicles while respecting **vehicle capacity**.  
This project mirrors Yulu’s real fleet rebalancing, maintenance, and servicing operations.

---

##  Key Features

- Solved using **Google OR-Tools** (Optimal CVRP)
- Compared with **Greedy Heuristic** baseline
- Real geographic distances using **Haversine formula**
- Interactive maps using **Folium**
- Clear performance comparison

---

##  Tech Stack

- **OR-Tools** (Google)
- **Folium** + **OpenStreetMap**
- **Python, Pandas, NumPy**
- **Haversine Distance**

---

##  Project Structure

```bash
yulu-vrp-optimization/
├── vrp_solver.py                    # Main code
├── locations.csv                    # Generated locations
├── greedy_routes.html               # Interactive map
├── or_tools_optimal_routes.html     # Best solution map
├── README.md
└── requirements.txt

Results

<img width="437" height="107" alt="image" src="https://github.com/user-attachments/assets/9b199767-9b59-40ed-81ef-c24dc534a53f" />

OR-Tools Optimal Routes (Best Solution)

<img width="957" height="477" alt="image" src="https://github.com/user-attachments/assets/6177a149-c956-40aa-98e3-b838bb709aeb" />



