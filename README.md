# Trains

Trains

Description

In the year 2030 to solve the traffic and air pollution problem of Tehran, the interior ministry finally decides to close all internal city streets except the main street, Vali -e Asr and start using elect rical trains. There is only one rail for these trains that is a simple polygon (a polygon that do not cross itself) and there are some trains on the rail. The figure shows a sample map of the rail and street. Ehsan wants to go from the most southern part o f Vali-e Asr to the most northern part. His problem is that he has an emergency work at the northern part so he wants to pass the street as quick as possible, but because he likes his life (!) he doesn't want his car to be crashed by any electrical train. The rail crosses the street in some points that we call cross point. Each train has a constant length and speed and when a train is going across the street, no car must be on the rail. No part of the rail is along the street. Ehsan knows the position of each train and he wants to schedule a driving plan in which he stops only on some cross points or on the starting point, and moving during other parts of the street by the known constant speed of his car (note that whenever he is stop on a cross point there must not be any trains passing the same cross point). Help him finding such a road. 

Input

Each test case begins with a line containing 6 numbers, in the following order: number of vertices of the rail ro ad (less than 50), number of trains (less than 20), coordinates of the end point, velocity of trains and velocity of Ehsan's car. In next lines, vertices of the road polygon are listed in the same order as trains visit them. Then, each train is described in a separate line by three numbers: coordinates of its head (x, y) and its length. No two trains intersect. y coordinate of the starting point is 0 and its x-coordinate is same as the end point. The final test case is started with 6 zeros.

Output

Write the length of the smallest period, during which Ehsan could safely go from south to west. This number must be rounded to four digits after decimal point and the output must contain exactly four digits after the decimal point. If Ehsan can't drive to the end point,just output "Impossible!".

Sample Input

4 1 10 30 1 2
0 10
30 10
30 20
0 20
5 10 5
0 0 0 0 0 0

Sample Output

20.0000
