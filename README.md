# Hardy-type nonlocality of Cyclic Entanglement

This repository contains simulations of Hardy-type nonlocality of the cyclic entanglement configuration of a four-particle system using quantum computers.

The notebooks are used in the paper titled "Hardy’s nonlocality for entangled pairs in a four-particle system". 
## Simulation
- Executed when Qiskit was in version 0.23.
- Quantum circuits are simulated through IBM's QASM simulator.
- Hardy-type nonlocality is observed through three sets of conditions ([Notebooks/Simulating Hardy-type nonlocality.ipynb](https://github.com/doan-duc1902/Hardy-nonlocality-of-cylic-entanglement/blob/main/Notebooks/Simulating%20Hardy-type%20nonlocality.ipynb)).
- The data for this notebook and the the sweep test are shown in ([Data/Simulation](https://github.com/doan-duc1902/Hardy-nonlocality-for-a-cylic-entanglement-setup/tree/main/Data/Simulation)).
## Theta sweep test
- Executed when Qiskit was in version 0.23.
- The experiment is also executed through IBM's QASM simulator.
- The results are shown in ([Notebooks/Theta sweep test_Hardy nonlocality.ipynb](https://github.com/doan-duc1902/Hardy-nonlocality-of-cylic-entanglement/blob/main/Notebooks/Theta%20sweep%20test_Hardy%20nonlocality.ipynb)).
## Practical examination on IBM Bribsbane
- Executed when Qiskit is in version 2.0.0.
- Due to resource constraints and limited time available for backend usage, each circuit in this experiment is only executed with 2048 shots, which is considerably smaller than that in simulation.
- The Brisbane results are shown in ([Notebooks/Hardy-type nonlocality on IBM_Brisbane.ipynb](https://github.com/doan-duc1902/Hardy-nonlocality-of-cylic-entanglement/blob/main/Notebooks/Hardy-type%20nonlocality%20on%20IBM_Brisbane.ipynb)).
- The data for this notebook are shown in ([Data/Brisbane](https://github.com/doan-duc1902/Hardy-nonlocality-for-a-cylic-entanglement-setup/tree/main/Data/Brisbane)).
- The comparision betwween Brisbane results and their simulation counterpart are shown in ([Notebooks/Comparision between Brisbane and simulation.ipynb](https://github.com/doan-duc1902/Hardy-nonlocality-of-cylic-entanglement/blob/main/Notebooks/Comparision%20between%20Brisbane%20and%20simulation.ipynb)).
## Identifying sources of deviations
- The IBM Brisbane's results, and the comparison of it with the simulation counterparts are shown in the Notebook ([Notebooks/Identifying sources of deviations.ipynb](https://github.com/doan-duc1902/Hardy-nonlocality-for-a-cylic-entanglement-setup/blob/main/Notebooks/Identifying%20sources%20of%20deviations.ipynb))
- The notebook of Brisbane results is executed with Qiskit 2.0.0.
- The simulation's result is shown in the Notebook ([Notebooks/Identifying sources of deviation_Simulation results.ipynb](https://github.com/doan-duc1902/Hardy-nonlocality-for-a-cylic-entanglement-setup/blob/main/Notebooks/Identifying%20sources%20of%20deviation_Simulation%20results.ipynb)), and it is executed with Qiskit 0.23.
- The reason for executing deviation-detection experiment on Brisbane and in simulation in two different Qiskit versions is that we want to have the consistency with the Hardy-type nonlocality experiments in the main parts.
- The data of both Brisbane and simulation for the identifying souurces of deviations experiment are shown in ([Data/Identifying-deviations-sources](https://github.com/doan-duc1902/Hardy-nonlocality-for-a-cylic-entanglement-setup/tree/main/Data/Identifying-deviations-sources)).
