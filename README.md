# gLyft Route Planner (C++)

**C++ project from ENGR 101**  
Plans galactic ride-sharing routes for a fictional company, gLyft, using the nearest-neighbor algorithm and correcting corrupted planetary data.

---

## Project Overview
gLyft wants to expand its ride-sharing service across multiple planets. This program calculates efficient routes for a gLyft driver to drop off passengers at all required planets while handling corrupted planet name data.

This project covers:

- Reading and processing input files (`locations.txt` and `names.txt`)
- Correcting corrupted planet names (removes "XX" and replaces underscores with spaces)
- Implementing the **Nearest Neighbor Algorithm** for route optimization
- Generating a route map and journey file (`journey.txt`)
- Using **vectors**, **structs**, **loops**, and **functions** in C++

**Educational Focus:** algorithm implementation, program design, modular code, testing, debugging.

---

## Technologies / Skills Demonstrated

- **Language:** C++
- **Data Structures:** `struct`, `vector`
- **Concepts:** File I/O, algorithm design, nested loops, helper functions, error handling
- **Engineering Intersection:** Computer Science & Engineering Entrepreneurship
- **Problem Solving:** Nearest Neighbor algorithm for route optimization, handling data corruption

---

## Project Structure

''' ├── route.h # Header file for Route helper functions '''
''' ├── route.cpp # Implementation of Route helper functions '''
''' ├── planRoute.cpp # Driver program containing main() '''
''' ├── locations_1.txt # Sample input file '''
''' ├── locations_2.txt '''
''' ├── names_1.txt '''
''' ├── names_2.txt '''
''' ├── journey_1.txt # Example output file '''
''' ├── journey_2.txt '''
''' └── README.md '''

---


### Example Output (journey.txt)

''' ..... '''
''' .XX.S '''
''' ..... '''
''' ..... '''
''' ..... '''
''' EQ... '''
''' ..A.. '''
''' X.... '''
''' ..P.. '''
''' ..... '''
''' ..... '''
''' T.... '''
''' Start at 2 5 '''
''' Go to Etheria and Eternia at 2 3 '''
''' Go to Domeo And James Juliett at 2 2 '''
''' Go to New Earth (Planet Bob) at 5 2 '''
''' Go to The Library at 6 3 '''
''' Go to The Discworld at 8 3 '''
''' Go to Jupiter Two at 7 1 '''
''' Go to Fhloston Paradise at 13 1 '''
''' End at 5 1 '''

## Features

- Corrects corrupted planet names (removes "XX", replaces underscores with spaces)
- Ignores planets outside the driver’s service range
- Flexible input (user specifies file names)
- Implements the nearest-neighbor TSP algorithm for route optimization
- Fully tested using multiple input cases

## What This Demonstrates

- Ability to design and implement a modular program from scratch
- Proficiency with C++ fundamentals (file I/O, structs, vectors, functions)
- Skill in debugging, handling edge cases, and producing robust output
- Exposure to algorithmic problem solving in a real-world engineering scenario
- Understanding of optimization problems like the Traveling Salesperson Problem (TSP)

