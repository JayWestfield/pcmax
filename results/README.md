
## Experimental Results

`all-exact-bounds.txt` lists all benchmarks with a known exact makespan, with that makespan.

`bounding_results.txt` shows the experimental results for all tested bounding techniques; see the header in that file for details.

The files `complete_*.txt` contain a complete run of each approach. Each line has the following space-separated columns:

1. File name
2. Running time (= 0 if exactly solved during bounding)
3. Found optimal makespan
4. Number of jobs $n$
5. Number of processors $m$
6. Ratio $n/m$
7. Memory usage in bytes (only available for some runs)
8. Number of explored nodes (only available for some runs)
