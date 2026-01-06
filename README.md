# Vicsek Collective Motion Simulator
**A high-performance Python implementation of the Vicsek Model for self-propelled particles.** 

### Project Overview
This simulator explores the emergence of collective behavior in active matter systems, such as bird flocks and fish schools.  [cite_start]It demonstrates how global order arises from simple local interactions without centralized leadership.  [cite_start]The project was developed as a final assignment for the Programming course at **ETSIAE-UPM**, where I achieved a grade of **9.4/10**. 

### Technical Highlights
* **Vectorized Architecture:** The core engine is built using **NumPy**, utilizing data-oriented design to avoid slow Python loops.  [cite_start]This allows for real-time simulation of hundreds of agents by processing system states as contiguous memory matrices. 
* **Toroidal Topology:** Implementation of periodic boundary conditions using the **Minimum Image Convention**.  [cite_start]This ensures a virtually infinite space, preventing artificial edge effects. 
* **Phase Transition Analysis:** The system includes a dedicated "Experiment Mode" to study the kinetic phase transition. [cite: 2] [cite_start]It automatically calculates the **Order Parameter (Φ)** against varying noise levels to identify the critical point where coordination collapses. 
* **Advanced Visualization:** Real-time rendering is handled via **Pygame**, providing a fluid graphical representation of the emergent clusters and alignment. [cite: 2]

### Project Structure
* `vicsek_simulation.py`: The main production script featuring the `VicsekSimulation` class, interactive console menu, and both Animation and Experiment modes. [cite: 2]
* `Vicsek_Analysis_Notebook.ipynb`: A comprehensive research notebook containing the physical foundations, mathematical proofs, and statistical analysis of the results. 
* `Vicsek_Model_Presentation.pptx`: The technical presentation used to explain the model architecture and findings. [cite: 1]

### Lead Developer Statement
I served as the **Lead Architect and Primary Developer** for this project. My responsibilities included:
* Designing and coding the entire physics engine and vectorized logic. [cite: 2]
* Implementing the toroidal boundary mathematics. 
* Developing the data analysis suite for phase transition plotting. 
* Coordinating the overall project structure and documentation. 

### Installation and Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/Vicsek-Collective-Motion.git](https://github.com/your-username/Vicsek-Collective-Motion.git)
