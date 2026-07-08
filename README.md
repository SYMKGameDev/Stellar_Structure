# Stellar_Structure
Models the stellar main sequence using a set of 5 coupled differential equations, which can be modified to account for the presence of magnetic fields. 

The main file is split into two analysis parts:
1. Creating a main sequence with or without modifications
2. Analysing individual stars from the main sequence

To create a main sequence, create a list of central temperatures (range from about 1e6 to 5e7) and run plot_main_sequence()

To analyze a star, pick a central temperature, run it through pcrootlist(), and then run the solution through plotting()

Below are some example plots created by the code.

A main sequence with varying magnetic field dissipation rates:
<img width="719" height="572" alt="image" src="https://github.com/user-attachments/assets/9e96fe3c-7f30-4de7-a210-d0fa1e88c7e2" />

A low mass star solution: 
<img width="1190" height="1590" alt="image" src="https://github.com/user-attachments/assets/811014c2-2de2-4696-87a6-c82d791d44d1" />

