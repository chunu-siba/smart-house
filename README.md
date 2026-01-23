# smart-house
🏠 Smart Home Simulation System A Python-based framework that models a modern smart home ecosystem using Advanced OOP concepts. The system simulates various household gadgets, manages room-specific environments, and tracks energy consumption in real-time.
🚀 Key Features
Hierarchical Device Architecture: Built a robust base class (SmartDevices) using Abstract Base Classes (ABC) to ensure consistency across all household tech.

Specialized Room Logic: Implemented unique room behaviors, such as:

Kitchen: Integrated a SmartFridge with automated inventory tracking and a real-time "Food Safety" internal temperature monitor.

Living Room: "Theater Mode" orchestration that dims lights and closes blinds simultaneously.

Bathroom: Humidity-sensing logic that auto-activates fans to prevent steam damage.

Energy Management Dashboard: A centralized system that aggregates power draw (Watts) from every active device across the house to calculate total utility load.

Automated Routines: Programmable Morning and Evening routines to toggle the state of the entire home with a single command.

🛠️ Technical Stack
Language: Python 3.x

Core Concepts: * Inheritance & Polymorphism: Extending base device functionality to specific appliances (AC, Fans, Bulbs).

Encapsulation: Managing device states (is_on, speed, brightness) through controlled methods.

Class Methods (@classmethod): Used for managing shared data, like the global grocery inventory for the fridge.

📂 File Structure
objects.py: Contains the class definitions and logic for all devices and rooms.

main.py: The execution script that initializes the house, installs gadgets, and runs the simulation routines.
