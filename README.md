# Tsdat Example Pipelines

This repository consists of submodules of tsdat ingest pipelines 
that have been used to process data. They contain common implementations
of tsdat functions and provide useful examples of how to incorporate
custom file readers and implement quality control functions. Raw data
to run these pipelines is stored in the "tests/data/input" folder and can
be run from the command line with `python runner.py <input_file>`.

These submodules are listed as follows:

1. WindSentinel_ingest: Pipelines that ingest processed lidar, IMU, current, and wave data from a Axys WindSentinel Buoy
2. MRE_resource_ingest: Processing pipelines for raw ADCP, ADV, and Sofar Spotter wave buoy data

Full instructions and tutorials to build a pipeline from scratch are located in https://tsdat.readthedocs.io/en/latest/examples_and_tutorials.html
