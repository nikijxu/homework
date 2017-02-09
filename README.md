# homework
homework of Niki Xu
below are my homework submissions. 

What native features of python support parallel programing?

The multiprocessing  module features of python support parallel programing. While offering both local and remote concurrency, it also effectively avoid the problems global interpreter lock might run into and allow programmers to fully leverage the multiple processors on a given machine. 

What native features of R support parallel programing?
Some extension features of r supports parallel programing such as:  Rmpi, rpvm, snow, nws or papply.
References: https://www.r-bloggers.com/parallel-computing-in-r/

What python libraries support parallel programing?
Libraries such as pp, pprocess,dispy support parallel programming. 
Reference: https://wiki.python.org/moin/ParallelProcessing

What R libraries/packages support parallel programing?
Libraries/packages including multicore, parallel,foreach, snowfall, doparallel, gbm, boot,lapply etc. (some do not attempt parallel operations unless specified) 
References: https://journal.r-project.org/archive/2009-1/RJournal_2009-1_Knaus+et+al.pdf


Can GPUs be used with python or R? If so, how?
GPUs can be used in conjunction with CPUs to boost parallel computing performance ( known as heterogeneous computing). GPUs are best suited to applying the same  computation over arrays of data, while CPUs are better suited to algorithms that include conditional branches of execution. 
