# -PhysicsInformedNNs-StepResponse-
Here’s a concise and professional README for your repository:

---

# PhysicsInformedNNs-StepResponse

This project explores the use of **Physics-Informed Neural Networks (PINNs)** to solve the unit step response of an underdamped second-order system. PINNs are used to solve differential equations by embedding the physics of the problem into the loss function of a neural network.

## Problem Overview  
The differential equation under study models the dynamic response of systems subject to a unit step input:
 >> d²y(t)/dt² + 2ζωₙ dy(t)/dt + ωₙ²y(t) = ωₙ²u(t) >>
 
### Key Features:  
- Solves for the response of an underdamped system (\(0 < \zeta < 1\)).
- Compares the PINN-based solution with the analytical solution.

## Project Highlights  
1. **PINN Design**:  
   - 2 hidden layers with Tanh activation.  
   - Physics-based loss function derived from the governing differential equation.

2. **Implementation**:  
   - **Libraries Used**: PyTorch, Matplotlib, NumPy.  
   - Code structured for clarity, including sections for analytical solutions, PINN training, and results visualization.

3. **Results**:  
   - PINN predictions closely match the analytical solution, validating its accuracy and efficiency.

## Repository Structure  
- **`notebook.ipynb`**: Jupyter notebook with the complete code for implementation and analysis.  
- **`README.md`**: This file for project description.  

## Future Improvements  
- Experiment with alternate architectures for better efficiency.  
- Apply PINNs to other dynamic systems for broader insights.  

---

Let me know if you'd like to customize it further or add anything specific!
