# Asynchronous_II
This repository contains the implementation and logs for the paper "Asynchronous Interval Iteration for Expected Rewards in Markov Decision Processes".
To run experiments:
 - enter the PRISM directory and type "make"
 - run .sh files for the experiments of the paper.
 
To run SCC-based methods properly for large models, set PRISM_JAVASTACKSIZE to higher values. (Edit /bin/prism and set PRISM_JAVASTACKSIZE to 400MB or more)
In some cases, upper bounds are set manually according to the related computed values from explicit engie. In these cases, the sparse engine does not provide finite upper bounds. 
