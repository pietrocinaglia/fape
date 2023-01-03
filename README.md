# FAPE

FAPE (Flexible Automated Pipeline Engine) is a software tool able to configure and deploy automated pipelines for Transcript-level Quantification from RNA-seq.


FAPE has been translated into a C program; it uses libpython and static C files of its own to execute in the same way as CPython does.
Note that the "requirements.txt" contains all dependancies need to FAPE, as well as to "monitor.py". The latter is a Python script stand-alone executable to monitor CPU and Memory usage (plotting is also supported); we used it for testing only.


### Cite this paper
Paper URL: https://link.springer.com/chapter/10.1007/978-3-031-22036-4_5

DOI: https://doi.org/10.1007/978-3-031-22036-4_5

Cinaglia, P., Cannataro, M. (2022). A Flexible Automated Pipeline Engine for Transcript-Level Quantification from RNA-seq. In: Guizzardi, R., Neumayr, B. (eds) Advances in Conceptual Modeling. ER 2022. Lecture Notes in Computer Science, vol 13650. Springer, Cham. https://doi.org/10.1007/978-3-031-22036-4_5


## How to run FAPE

> ./FAPE.bin pipeline.json SAMPLES_DIR=samples P1_TIME=5 P2_PAR1=P2 P2_TIME=5

Alternatively, you can insert parameters manually through:

> ./FAPE.bin pipeline.json

or:

> ./FAPE.bin


Notes: FAPE supports Unix-like Operating Systems; it has been tested on MacOS.


## Testing
A testing pipeline based on the module (i.e., 'test') located into 'modules' is available. Furthermore, a set of synthetic files (.fq.gz) are located into 'samples'.
Note that both testing module and synthetic files DO NOT PRODUCE an output, these are only for testing.
We invite you to use a real pipeline based on non-testing modules to produce a valid output.


## MIT License

Copyright (c) 2022

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.