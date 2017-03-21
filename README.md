# roch_concert

Concert for multi Roch usecases.

## Configuration 
We assume you have two machine, a concert PC and a laptop of Roch.
Conert PC
========
export ROS_HOSTNAME=IP_OF_PC
export ROS_IP=IP_OF_PC
export ROS_MASTER_URI=http://IP_OF_PC:11311

Laptop Roch
========
export ROS_HOSTNAME=IP_OF_ROCH
export ROS_IP=IP_OF_ROCH
export ROS_MASTER_URI=http://localhost:11311

## Usage

Bringup concert PC ```concert.launch```
```
roslaunch roch_concert concert.launch
```

Start concert client Roch with ```concert_client_old.launch```
```
roslaunch roch_bringup concert_client_old.launch
```
