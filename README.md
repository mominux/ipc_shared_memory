# ipc_shared_memory
This repository contains a simple example of interprocess communication between a sensor and two actuators using Boost.Interprocess library. The sensor generates random temperature readings and writes them to a shared memory segment. The two actuators read the temperature data from the shared memory and perform some processing on it.

The repository contains three main files:

sensor.cpp: generates random temperature readings and writes them to a shared memory segment.
actuator1.cpp: reads the temperature data from the shared memory and prints it to the console.
actuator2.cpp: reads the temperature data from the shared memory, extracts the message and tag, and prints them to the console.
The communication between the processes is synchronized using named semaphores. The repository also includes the necessary Boost libraries as submodules and a CMake build file to build the example.

This example is meant to demonstrate a simple use case of Share memory with Boost.Interprocess and provide a starting point for more complex interprocess communication scenarios. 

take a lokk to my webssite and read my weblog : www.mominux.com/
