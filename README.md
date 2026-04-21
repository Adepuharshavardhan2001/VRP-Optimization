## Hyderabad Route Optimizer (VRP)

A Python-based logistics tool that uses Google OR-Tools to calculate the most efficient delivery routes for multiple vehicles starting from a central depot in Hitech City, Hyderabad.

# Features

Multi-Vehicle Routing: Optimizes paths for a fleet of vehicles (currently configured for 2).

Distance Matrix Calculation: Uses Euclidean distance between GPS coordinates (Lat/Lon).

Interactive Visualization: Renders optimized routes on an interactive map using folium.

Constraint Solving: Minimizes total travel distance using the PATH_CHEAPEST_ARC strategy.

# Tech Stack

Python 3.11

OR-Tools: Google's optimization software for combinatorial optimization.

Pandas: Data manipulation and location management.

Folium: Leaflet.js integration for geographical mapping.

SciPy: Efficient distance matrix computation.

# Getting Started
1. Prerequisites

Ensure you have Python installed, then install the necessary libraries:

Bash

pip install pandas scipy ortools folium

2. Running the Optimizer

The script defines 10 key locations in Hyderabad, including:

Depot: Hitech City

Delivery Points: Gachibowli, Madhapur, Jubilee Hills, Charminar, etc.

Simply run the notebook or script to generate the route output:

Vehicle 1 Route:
Depot → Gachibowli → Kondapur → Madhapur → Ameerpet → Begumpet → Secunderabad → Jubilee Hills → Charminar → Banjara Hills → Depot

# visualisation

# Greedy_VRP 

<img width="956" height="491" alt="Screenshot 2026-04-21 061816" src="https://github.com/user-attachments/assets/2856571a-c377-4778-8dd2-aeefc32b9162" />

# OR Tools

<img width="958" height="470" alt="or tools" src="https://github.com/user-attachments/assets/64e70544-6f88-4d4a-93a0-1ecf6ca71287" />



Vehicle 1 Route:
Depot → Gachibowli → Kondapur → Madhapur → Ameerpet → Begumpet → Secunderabad → Jubilee Hills → Charmi
