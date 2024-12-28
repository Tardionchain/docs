---
title: How Does Tardi Work? (Current State)
---
Currently, Tardi is in the foundational phase, focusing on simulating a simplified neural architecture while integrating real-time data processing and interactive visualizations.

## Key Components

### 1. Neural Network Simulation
The simulation models the neural activity of a tardigrade, focusing on the following types of neurons:
- **Movement Command Neurons:** Control forward, backward, and turning movements.
- **Motor Neurons:** Direct muscle activity to execute movements.
- **Muscle Neurons:** Represent the organism’s physical structure and movement output.
- **Sensory Neurons:** Process environmental stimuli, such as touch and light.
- **Interneurons:** Facilitate communication between other neurons.

These neurons interact dynamically to simulate real-time behavior, with weights and states updated based on environmental inputs and system interactions.

### 2. Dynamic Weight Adjustments
Tardi’s neural connections evolve over time using a dynamic weight adjustment mechanism. The system:
- Fetches real-time data from the blockchain or simulated inputs.
- Processes the data to calculate updated connection weights.
- Applies these weights to simulate adaptive behavior, mimicking learning processes in biological systems.

### 3. Visualization
The neural network’s activity is visualized in real time through a canvas-based frontend. Users can:
- Observe neuron interactions and states.
- Explore how stimuli influence behavior.
- Interact with the system to see adaptive changes.

### 4. Movement and Environmental Response
Tardi simulates basic tardigrade behaviors, such as:
- **Movement:** Responding to directional commands based on sensory input.
- **Environmental Interaction:** Reacting to stimuli like light or touch, driven by sensory neuron signals.

The “MovementStore” component manages data synchronization for position and movement updates, ensuring a cohesive and responsive simulation.

## Current Achievements
- A functional prototype of the neural simulation, including basic neuron types and interactions.
- Dynamic weight adjustment mechanisms that adapt neural states based on real-time data.


