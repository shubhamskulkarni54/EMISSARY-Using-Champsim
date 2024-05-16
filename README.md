This repository contains the code for our implementation of EMISSARY (Enhanced Miss-Cost Aware Cache Replacement Policy). Before reading further please note that, **EMISSARY is a Level 2 Cache replacement policy, if you try to implement it on the LLC the performance may hamper depending on the working set size of your benchmarks.**

I have uploaded the paper associated with the EMISSARY budget, the credits for the idea are reserved with the authors.

In this implementation we haven't made any changes to the default structure of the Champsim Simulator (If you are new to the Champsim click this link: https://github.com/ChampSim/ChampSim). We have tried to keep implementation as simple as possible and also tried to minimize the hardware budget which both are core ideas behind the EMISSARY as per the authors. 

The file **my_replacement.cc** contains the C++ code for the policy, you can create a new folder under replacements in the default repo of the Champsim and test the code. 
The images uploaded showcase the speedup we were able to achieve on different configurations of cache sizes and the traces that were available to us.
