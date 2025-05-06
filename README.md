# Minor_project_traffic_management
Urban traffic congestion is a growing challenge, particularly in the context of rapidly developing smart cities.
Traditional traffic signal systems rely on fixed-time control strategies that fail to adapt to real-time traffic
dynamics, leading to increased congestion, fuel consumption, and environmental pollution. To address these
limitations, this project implements an intelligent traffic signal control system based on Deep Reinforcement
Learning (DRL) techniques, specifically using Deep Q-Networks (DQN).
The system is designed to optimize traffic flow at intersections by learning from real-time traffic patterns. It
selects signal actions that minimize queue lengths and waiting times while maximizing throughput. The
environment is modeled using SUMO (Simulation of Urban MObility), allowing for the simulation of
realistic traffic scenarios. Through interaction with the environment, the agent learns an optimal policy that
dynamically adjusts traffic signals based on current vehicle distributions and movement trends.
Key technical contributions of the project include the design of an advanced state representation, a custom
reward function balancing efficiency and fairness, and techniques to ensure training stability in a complex,
dynamic environment. The system was evaluated against traditional fixed-time signal control, showing
significant improvements in reducing average waiting times, queue lengths, and improving overall intersection
efficiency.
Overall, this project successfully illustrates the power of DRL in creating adaptive, intelligent, and efficient
traffic control systems, offering a viable path forward for modern urban traffic management and laying the
foundation for real-world deployment in intelligent transportation networks.

