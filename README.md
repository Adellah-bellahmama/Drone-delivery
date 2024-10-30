# Drone-delivery
This project implements a drone-based delivery system inspired by the Kaggle competition organized by Google, titled “Hash Code Archive: Drone Delivery.” The primary objective of this project is to solve the Unmanned Aerial Vehicle Routing Problem (UAVRP) using a parallel genetic algorithm, optimizing drone operations for effective logistics management.

Key Features:
Problem Formulation:

The system addresses the complexities of split deliveries, multiple depots, and multi-product components, emphasizing efficient logistics within the context of the competition.
Genetic Algorithm Implementation:

The algorithm optimizes drone routing by minimizing delivery time and distance while managing various logistical constraints presented in the competition.
Parameters of the genetic algorithm, including population size, mutation rate, and crossover rate, were carefully tuned to enhance solution quality.
Dynamic Drone Reassignment:

The system incorporates a mechanism for dynamically reassigning drones after each delivery. Drones are evaluated for their next assignment based on their last delivery location and available orders, reducing idle time and maximizing efficiency.
Scalability and Adaptability:

This delivery system can handle logistics for a large number of customers (up to 1,250) across multiple trips, drones, and warehouses, with support for various product types, reflecting the competitive nature of the challenge.
Performance Metrics:

The optimized solution demonstrated a 30% improvement over the initial baseline, highlighting the effectiveness of the modifications made to the original code.
Code Structure:
Modules:

The code is organized into several modules, each addressing different components of the delivery system, including:
Warehouse Management: Functions to manage warehouse inventory and allocate orders.
Drone Operations: Logic for assigning drones to orders and planning routes.
Genetic Algorithm: Implementation of selection, crossover, mutation, and evaluation processes.
Simulation Loop:

A central simulation loop iterates through the delivery process, monitoring drone status, order fulfillment, and performance metrics to assess the efficiency of the logistics strategy.
Future Work:
Potential enhancements could include optimizing routes based on real-time data.
Usage:
The code is designed to run in a Python environment with the necessary libraries installed. Detailed instructions for setup and execution are included in the repository.
