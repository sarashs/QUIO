# QUIO
Quadratic Unconstrained Integer Optimization on PYNQ-Z1

## Requirements:

- PYNQ Z-1 board.
- PYNQ image version 2.6.
- One working hand (for typing).
- Some knowledge of Dwave QUBO (Mine is the digital integer version)

## What I provide (Version 0):

- At this point we have 256 fully connected uint32 nodes where the couplings between the nodes and the bias (magnitude) on each node is a float32 value.

- Copy the bit stream file and the hardware handout file into your pynq overlay folder. Copy the Jupyter notebook into your pynq notebook folder. Modify the path to the overlay within the notebook and run it. A short tutorial is given in the notebook.

- A simple driver is also provided in the notebook.

## What I will provide in the future:

- HDL code of the QUIO solver and some performance metrics
