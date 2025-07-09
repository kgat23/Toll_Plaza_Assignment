# Toll Plaza Assignment

A Spring Boot application that simulates toll plaza detection between two Indian pincodes using a mock route and a static toll list.

## Features

- Accepts source and destination pincodes
- Returns toll plazas within 25 km of a predefined route
- Simulated distance between source and destination
- Caching for repeated requests
- Handles invalid and edge-case inputs

## Disclaimer

This project does not use any real-time mapping APIs.  
It uses a **hardcoded route from Bangalore to Pune**, so the output will remain the same regardless of the input pincodes.

## How to Run

1. Clone the repository and navigate to the project:
   ```bash
   git clone https://github.com/kgat23/Toll_Plaza_Assignment.git
   cd Toll_Plaza_Assignment/tollapi
