/* Add Author and Project Details here */
 Name : Geeta Navalyal

 Project Details:

To create a Makefile to build an application ( to do some arbitrary memory reads and writes) on two platforms, the host platform and an ARM based MSP432 platform.

NOTE: make clean command has to be executed whenever files are edited or platforms are changed

Steps (commands) to run the make file

1. On HOST platform,
  > cd Assignment2/src 
  > make build PLATFORM=HOST
  > ./c1m2.out 
     Outputs : aXy72_L+R
  > make clean

2. On MSP432 ARM platform,
  > cd Assignment2/src
  > make build PLATFORM=MSP432
    Creates an executable (binary) c1m2.out
  > make clean



