### About
Sources and benchmarks for the following papers:

Oleg Zaikin. Inverting 43-step MD4 via Cube-and-Conquer // In IJCAI 2022.

Oleg Zaikin. Inverting Cryptographic Hash Functions via Cube-and-Conquer // JAIR 2024.

### Directories overview

/cnfs_ijcai - CNFs used in the IJCAI experiments, as well as TA-programs for the Transalg tool.

/cnfs_jair - CNFs used in the JAIR experiments, as well as TA-programs for the Transalg tool.

/src_ijcai - IJCAI sources.

/src_jair - JAIR sources.

/solutions_jair - solutions found in the JAIR experiments.

### Sources

find_cnc_threshold.py - finds a threshold for cubing phase of Cube-and-Conquer.
For each threshold, a runtime estimation is calculated. This script can be
applied to an arbitrary CNF to estimate its hardness and/or to properly apply
Cube-and-Conquer.

boxplot_solvers.py - plots boxplots to visualise the estimations for thresholds.

sort_solution.py - sorts a given satisfying assignment by variable number,
extracts the first 512 bits (preimage) and converts them to a hex integer.

conquer.cpp (parallel_cubes.cpp in IJCAI sources) - multirhreaded implementation
of the conquer phase of Cube-and-Conquer.

### Citation
If you use these sources or/and data, please cite:
```
@inproceedings{Zaikin-IJCAI22,
  author    = {Oleg Zaikin},
  title     = {Inverting 43-step {MD4} via {Cube-and-Conquer}},
  booktitle = {IJCAI-ECAI 2022},
  pages     = {1894--1900},
  year      = {2022}
}
```
or

```
@article{Zaikin-JAIR2024,
  author    = {Oleg Zaikin},
  title     = {Inverting Cryptographic Hash Functions via {Cube-and-Conquer}},
  journal   = {JAIR},
  year      = {2024}
}
```
