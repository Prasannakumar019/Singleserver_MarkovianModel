## EX NO:07
## DATE:15.6.22
# <p align="center">Single server infinite capacity - Markovian Model

# Aim : 
To find 
      (a) average  number of materials in the conveyor
      (b) suitable length of conveyor
      (c) waitinging time of the material in the conveyor,
if arrival rate of material  follows poisson process 5 per minuates and serivice rate of lathe machine follows 
exponential distribution with mean serice rate 6 per minutes.


# Software required :  

Visual components and Python

# Theory:

  Queuing are the most frequently encountered problems in everyday life. For example, queue
at a cafeteria, library, bank, etc. Common to all of these cases are the arrivals of objects
requiring service and the attendant delays when the service mechanism is busy. Waiting lines
cannot be eliminated completely, but suitable techniques can be used to reduce the waiting
time of an object in the system. A long waiting line may result in loss of customers to an
organization. Waiting time can be reduced by providing additional service facilities, but it may
result in an increase in the idle time of the service mechanism. 

![image](https://user-images.githubusercontent.com/104613195/173292918-2583e4d3-a3d8-45fa-a577-9d0ebf79f0a5.png)


![image](https://user-images.githubusercontent.com/104613195/173292021-8c3b77dc-a9c2-4179-91ed-17e1db7039df.png)


 
# Procedure :
 
1. Calcualte average number of materials to be waitted in the conveyor using given data.
2. Create a empty project  in visual component tool and add visual legacy component to the project.
3. Drag a feeder and place in a place and choose the appropriate materal.
4. Calculate conveyor length usng material size and average number of materials to be waitted in the conveyor
5. Choose the two conveors from components,  add one conveyor with feeder.
6. Drag Lathe machne from machine library and place in the appropirate place.
7. Drag machine trending inlet and outlet from visual legacy and add them to the two conyeors in the approprate manner.
8. Drag robot manager and robot from visual legacy and place in between two conveyors.
9. Connect all machine trending  inlet, outlet, robot manager and lathe machine using interface menu.
10. Run the program.
# Experiment:
![55](https://user-images.githubusercontent.com/75235090/175531961-dfee531c-8d4b-41f9-b089-6cf4114e8310.png)

# Program :
```
Developed by:
 Register Number:212220230035
 Name:Prasannakumar M  
 ```
![56](https://user-images.githubusercontent.com/75235090/175532133-4159ea37-924a-4658-8e61-b87aa0f38156.png)

# Output : 
 ![57](https://user-images.githubusercontent.com/75235090/175532238-68f09be0-a77e-47d1-82a0-d9975b96c09f.png)

## Result:
The average number of materials in the system is 4 and the conveyor is 3.2, and average waiting time of each materials in the system is 60 seconds and conveyor is 48 seconds are calculated.
