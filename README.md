# CharmedDataSet

This is the dataset for the paper "The Charming Code that Error Messages are Talking About," currently on submission for peer review.

The input files are all of the Python files in the lib/ directory.

The output files are `charm.csv` which lists information (including charm) for each line of each input file, and `detailed_log.csv` which lists information for each mutant tested. `detailed_log.csv` is broken into multiple parts due to Github's file size limit, and can be concanentated. `perblock.csv` includes per-block information including the information produced by the `radon` tool.
