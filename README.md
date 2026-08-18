# Physics-informed Data-driven Modeling of a Two-DoF Robot Arm
Utilized JAX and Keras for an optimized implementation of Lagrangian Neural Networks. This model was used for learning the dynamics of a two-DoF robot arm.

## Two-DoF Robot Arm
<img width="390" height="418" alt="image" src="https://github.com/user-attachments/assets/13daa019-7373-4ae6-98bd-69d958df44a2" />

## How to Use
1) Install the required Python modules (Keras, JAX, MuJoCo, NumPy, and Matplotlib).
2) Clone the repository
3) "model.xml" is the MuJoCo model of the robotic arm, written in MJCF. You can view it by a drag-and-drop into MuJoCo's Simulate GUI.
4) Run the "LNN.ipynb" notebook. It will automatically simulate and generate a dataset of random trajectories for the two-DoF arm and stores it as a single file "XAU_data.npz" for later use. Then, it reloads the stored dataset and the PINN training begins.
