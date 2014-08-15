rprime
======

`rprime` is an R package for parsing `.txt` generated by E-Prime, a program for running psychological experiments. Development is active and on-going.

## Overview

The main workflow for working with `rprime` involves:

1. `read_eprime`: reliably read in data from an Eprime log (`.txt`) file.
2. `extract_frames`: extract the text in each `"LogFrame"` in the file, storing each log-frame as an R list.
3. `preview_levels`, `preview_eprime`: explore the structure of the parsed data.
4. `keep_levels`, `drop_levels`, `filter_in`, `filter_out`: select and filter particular levels from the txt-file..
5. `to_data_frame`: make a data-frame from the parsed data.

