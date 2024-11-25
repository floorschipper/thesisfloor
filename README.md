# thesisfloor
This repository contains all the code used for the computations in the MSc thesis *placeholder*. 

# requirements
Execution of the code requires the following:
- Python 3.10
- SageMath
- [gcaops](https://github.com/rburing/gcaops)
- at least 32GB RAM

It is recommended to use the native SageMath environment for Linux for execution, either through a container runtime such as Docker, installation using conda, or building from source. It is possible to utilize WSL2 for virtualized execution on a Windows machine. Refer to [the Sage Installation Guide](https://doc.sagemath.org/html/en/installation/index.html) for more information on installing SageMath.
Note that `gcaops` by default utilizes all available CPU cores. It is recommended to either manually override the number of CPU cores used, or execute the code on dedicated computing hardware.

Increases in cocycles and dimension require increasing amounts of memory. While computation related to gamma 3 up to dimension 4 can be executed on sufficiently powerful consumer hardware, access to a high performance computing cluster might be necessary.

# instructions
As the majority of code has the same principles in common it is recommended to start at the code used for the uniqueness aspects of Kontsevich graphs, and continue from there.
