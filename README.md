# ietest
Test IE Submitted on the 4th of July

The code runs in the following format:

Commands such as

PLACE X,Y,F is put as an array like [0,[x,y,d]]

MOVE is the number 1

LEFT is the number 2

RIGHT is the number 3

REPORT is the number 4

Test data as below:

[1,6,1,4,[0,[0,3,3]],1,0,2,3] - move, invalid, move, report, place 0,3,3(EAST), move, invalid, left, right
[[0,[1,0,3]],1,1,1,1,[0,[2,4,3]]] - place 1,0,3(EAST), move, move, move, move, place 2,4,3(EAST)
