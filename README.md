Procedural programming: liquid container

- add amount adds the amount of liquid specified by the parameter to the first container. The inserted amount must be specified as an integer. The container can't hold more than a hundred liters and everything added past that will go to waste.
- move amount moves the amount of liquid specified by the parameter from the first container to the second container. The given amount must be specified as an integer. If the program is requested to move more liquid than than the first container currently holds, move all the remaining liquid. The second container can't hold more than one hundred liters of liquid and everything past that will go to waste.
- remove amount removes the amount of liquid specified by the parameter from the second container. If the program is requested to remove more liquid than the container currently holds, remove all the remaining liquid.

- Sample output

- First: 0/100
- Second: 0/100
#remove 10


- First: 0/100
- Second: 0/100
#add 20


- First: 20/100
- Second: 0/100
#remove 5


- First: 20/100
- Second: 0/100
#move 15


- First: 5/100
- Second: 15/100
#remove 5


- First: 5/100
- Second: 10/100
#remove 20


- First: 5/100
- Second: 0/100
#quit
