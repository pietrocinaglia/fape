# Flexible Automated Pipeline Engine (FAPE)
A Flexible Automated Pipeline Engine (FAPE) for Transcript-Level Quantification from RNA-seq.

## Cite FAPE
Pietro Cinaglia and Mario Cannataro. 2023. A Flexible Automated Pipeline Engine for Transcript-Level Quantification from RNA-seq. In Advances in Conceptual Modeling: ER 2022 Workshops, CMLS, EmpER, and JUSMOD, Hyderabad, India, October 17–20, 2022, Proceedings. Springer-Verlag, Berlin, Heidelberg, 45–54. https://doi.org/10.1007/978-3-031-22036-4_5

## Abstract
The advances in massive parallel sequencing technologies (i.e., Next-Generation Sequencing) allowed RNA sequencing (RNA-seq). The analysis of RNA-seq data uses a large amount of computational resources, and it is very time-consuming. Usually, the processing is performed on a large set of samples, and it is convenient designing an automatic pipeline to eliminate the downtime. The pipelines represent an advantage, however these are difficult to customize, or to use outside the specific context for which they have been tested.
In this paper, we propose FAPE (Flexible Automated Pipeline Engine), a software platform to configure and to deploy automated pipelines. It models a pipeline based on a given template. The latter has a highly understandable and manipulable organization, to meet the operator’s need for customization. In addition, a scientist may model an in-house custom pipeline able to execute all tools based on a command line interface (CLI). FAPE supports both parallel and iterative processes, in order to analyze whole datasets. We tested our solution on a pipeline for Transcript-level Quantification from RNA-seq, based on Hisat2, SamTools, and StringTie. It exhibited high robustness as well as inherent flexibility in supporting any pipeline modeled to specification. Furthermore, it has proven not to be expensive in terms of memory, and it does not introduce a significant latency during the execution, as compared to a pipeline executed through a shell-script program. In addition, the statement parallel of FAPE allowed during the test a reduction of the total elapsed time of .

## Update
This repository will no longer be maintained.

FAPE has been extended by including several improvements and novel features, therefore, it merged into the FLENP project (https://github.com/pietrocinaglia/flenp).

