# Traffic Simulation Project

## Project Goals
This project aims to develop an agent-based traffic simulation model, designed to analyze and understand urban traffic flow dynamics and improve traffic management strategies.

## Simulation Plan
The simulation includes the following components:
- **Vehicle**: Represents cars with properties like position, speed, and state.
- **TrafficSignal**: Manages traffic flow at intersections, directing vehicles based on signal states.
- **Road**: Serves as the pathway for vehicles, defining lanes and connections.
- **Intersection**: Connects roads, regulating vehicle movement through TrafficSignal interactions.
- **Environment**: Contains all components, coordinating their interactions within the simulation.

## Documentation
- **Literature Review**: Found in `docs/Literature_Review.pdf`, summarizing traffic simulation models.
- **UML Diagram**: Located in `docs/UML_Diagram.png`, depicting component interactions.
- **Planned Tests**: Test cases are outlined in `tests/` for verifying functionality.

## How to Run
Instructions for running the simulation will be added as the project develops.

## Future Enhancements
Potential improvements include emergency vehicle prioritization, pedestrian crossings, and variable traffic signal timings.

Q&A

## Why NetLogo?
NetLogo was chosen because it excels at agent-based modeling, allowing each car to operate as an independent agent that makes localized decisions based on its environment. In this project, where the focus is on how car agents' reaction behaviors (acceleration and deceleration) impact overall traffic flow, NetLogo’s ability to easily model individual behavior and observe emergent system patterns is crucial. Additionally, NetLogo provides built-in tools for real-time visualization, simple parameter adjustment (such as acceleration values), and automatic data plotting, making it ideal for iterative experimentation with vehicle dynamics.

## Real-World Traffic Principles Applied?
- Driver Reaction Behavior: The model simulates how individual drivers accelerate and decelerate based on nearby vehicles and traffic signals, mirroring real-world driver decision-making under varying traffic conditions.

- Congestion Formation from Local Decisions: Traffic jams and slowdowns in the model emerge from the collective effects of many small, local reactions by individual car agents — just like in real-world urban traffic, where human drivers' micro-decisions cause system-wide congestion.

- Signalized Intersections: Traffic lights regulate vehicle movement at intersections, representing real-world systems where driver agents must respond to light changes appropriately.

- Traffic Density Sensitivity: As the number of car agents increases, the simulation models how individual car behaviors amplify or dampen congestion, reflecting how real-world traffic flow deteriorates at higher vehicle densities.
