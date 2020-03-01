# FlightGear-Simulator in cpp

Flight simulator by cpp program

## Description
In this project we will take .txt file convert it to a Commands which flight-simulator recongnize and deliver them to the server by continuous connection.

Git-hub [link](https://github.com/AmitMalkan404/super-duper-invention)


## Installation

Download FlighGear server from [here](https://flightgear.org/download/)

Recommendation for environment [Clion](https://wiki.cs.huji.ac.il/wiki/Installing_CLion_on_Linux) 

## Usage

```bash
1. Open FlightGear -> Settings -> Additional Settings and write the next commands:
    "--telnet=socket,in,10,127.0.0.1,5402,tcp"
    "--generic=socket,out,10,127.0.0.1,5400,tcp,generic_small"
2. Take all the .h and .cpp file and put in your project
    - locate "fly.txt" (the file commands) in "cmake-build-debug" folder.
    - locate the .xml in "Protocols" folder where you installed your simulator.
3. Run the c++ project with one argument-commands text.
4. Click "fly" in the simulator.
5. Have a pleasure flight.
```

## Technologies



```bash
Programed in c++ language.
Compiled with c++ ver14
Simulated with "FlightGear" simulator.
```

## Contributing
You are more than welcome to change bugs or offer a better way for anything, here my email for sharing thought or questions stavih19/amit.malkan@gmail.com

## Learning Techniques

```bash
Open socket to communicate with server and client
Working with external server
Using multi-thread working
```

## MIT
[MIT](https://choosealicense.com/licenses/mit/)
