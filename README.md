# Museum-Path-Optimization

- [Museum-Path-Optimization](#museum-path-optimization)
  - [Group Members](#group-members)
  - [Description](#description)
    - [Data Input](#data-input)
    - [Simple Simulated Annealing](#simple-simulated-annealing)
    - [Complex Simulated Annealing](#complex-simulated-annealing)
  - [Project Tree](#project-tree)

## Group Members
*In alphabetical order:*

Apurva Kulkarni, Arsh Khan, Harshal Kataria, K T Prajwal Prathiksh, Miloni Atal, Mridul Agarwal, Patel Joy Pravin Kumar, Nakul Randad, Souvik Kumar Dolui, Umang Goel

## Description
Contains code meant to optimize the route for a tourist visiting the Louvre Museum, such that the satisfaction level is maximised by visiting all/select exhibits in a single working day. 

This repository represents the work done as part of the course project for AE - 755: Optimization for Engineering Design *(Spring 2020)*, [Prof. Abhijit Gogulapati](https://www.aero.iitb.ac.in/home/people/faculty/abhijit), Indian Institute of Technology Bombay.

Instructions on running specific algorithms are mentioned below:

### Data Input
To generate and store the cost matrices of all the test cases, do the following:
```
$ python code/data_input/base_input.py
```

### Simple Simulated Annealing

To run the simple simulated annealing algorithm, do the following:
```
$ python code/simulated_annealing/simple_simulated_annealing.py
```

Run the following to get all the command-line arguments:
```
$ python code/simulated_annealing/simple_simulated_annealing.py -h
```

### Complex Simulated Annealing

To run the complex simulated annealing algorithm, do the following:
```
$ python code/simulated_annealing/complex_simulated_annealing.py
```

Run the following to get all the command-line arguments:
```
$ python code/simulated_annealing/complex_simulated_annealing.py -h
```

## Project Tree
```
.
├───code
│   ├───ant_colony
│   ├───branch_and_bound
│   ├───data_input
│   │   └───__pycache__
│   ├───genetic
│   ├───simulated_annealing
│   └───__pycache__
├───data
│   ├───cost_matrices
│   └───Symmetric_TSPLIB
├───output
│   └───simulated_annealing
│       └───figures
└───reports
```
