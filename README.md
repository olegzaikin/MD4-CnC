# DESCRIPTION
Sources and benchmarks for the paper 'Inverting 43-step MD4 via Cube-and-Conquer' accepted to IJCAI-ECAI-2022.

## DIRECTORY OVERVIEW

/cnfs - all CNFs used in the experiments, as well as TA-programs for the Transalg tool.
/src - sources.

## SOURCES

find_cnc_threshold.py - finds a threshold for cubing phase of Cube-and-Conquer.
boxplot_solvers.py - plots boxplots to visualise the estimations for thresholds.
parallel_cubes - multirhreaded implementation of the cubing phase of Cube-and-Conquer.

## CITATION
If you use these sources, please cite the paper:

@inproceedings{Zaikin-IJCAI22,
  author    = {Oleg Zaikin},
  title     = {Inverting 43-step {MD4} via {Cube-and-Conquer}},
  booktitle = {IJCAI-ECAI 2022},
  pages     = {in press},
  year      = {2022}
}
