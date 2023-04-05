# yolo_time
#YOLO timer: exposes dangerous interrupt disabling routines from kernel 
This module was built to go with [this blogpost](XXX) 

It allows userland code to do very unsafe things to the scheduler  in ring0.
It does this in the name of science. Specifically, the precise measurement of instruction level timing info

The following [paper from intel](https://www.intel.com/content/dam/www/public/us/en/documents/white-papers/ia-32-ia-64-benchmark-code-execution-paper.pdf)  serves as good starting point.

