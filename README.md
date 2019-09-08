* This is my operating systems course project.
* A Virtual Implementation of routines of OS.
* Works for any number of Jobs .
* Supports input spooling ,output spooling ,paging ,error detection .

#### MOS ( Multiprogramming Operating System)

* Used for execution of multiple jobs 
* Job should be defined ,well structured
* System Will Report Error ,For Wrong Jobs With Proper Error Messages.
* Series of Jobs should be kept in input.txt
* Afer processing of jobs output can be seen output.txt
* Random memory allocation for program card using paging.

#### Job can consist of Instruction

* GD-Get Data
* PD-Print Data
* LR-Load Register From Memory
* SR-Store Register From Memory
* CR-Compare Register And Memory
* BT-Branch Toggle(Checks Toggle Variable)
* H- Denotes end of job.
* Job should start with $AMJ
* There is $DTA after declaration of program cards and before data cards
* Job should end with $END

#### Tools used
* Gcc compiler
* Emacs
* Gdb

