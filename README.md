# Finding Ground States Using NetKet

Authors: Akash Shukla, Bishoy Kousa, Carson McVay, Leslie Zhang

# Introduction

This is a repo for the PHY 381c final project. The project focuses on applying NetKet to minimize Hamiltonians and compute the ground states. Netket is a jax-powered machine learning toolbox specifically designed for quantum systems. 

In quantum mechanics, we can use the variational principle to find an upper bound on the ground state energy. We want a tighter bound on the ground state, which requires finding optimal paramaters that minimize the energy of a trial state. The curse of dimensionality makes it difficult to find the optimal parameters because the size of the Hilbert space grows exponentially with the system size. This leads to both memory and run time problems. We can use Monte Carlo sampling as a way to estimate large sums (which allow us to compute the energy) by sampling a much smaller number of terms. NetKet is a framework for using Monte carlo sampling in order to get a better bound on ground state energy. Our presentation (linked [here](https://docs.google.com/presentation/d/1rX2EZ6sUIktVCD3ArwPOyoeWIvdj3H1PSjhSOW63Bb4/edit?usp=sharing)) contains more information of the benefits of using NetKet as well as the results of applying NetKet for various Hamiltonians. More information on NetKet can be found in a series of Youtube videos by ICTP condensed matter and statistical physics. ([Linked here](https://www.youtube.com/watch?v=d0DK9J-DgR0&list=PLYc-eBoIpXTJtBdK2VPv5w7bX9P7qmsQV&index=8))

# Package Requirements
to install packages run command 
pip install -r requirements.txt

# Examples
[The Basic Tutorial](https://github.com/carsonmcvay17/class_project/blob/main/ground_states_tutorial.ipynb)
[Nearest Neighbors Hamiltonian](https://github.com/carsonmcvay17/class_project/blob/main/next_nearest_neighbors.ipynb)
[Different Polarization Hamiltonian](https://github.com/carsonmcvay17/class_project/blob/main/different_polarization_Hamiltonian.ipynb)
[Feed Forward Implementation](https://github.com/carsonmcvay17/class_project/blob/bkousa-patch-1/ground_state_NN.ipynb)