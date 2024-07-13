# Rock-Paper-Scissor
This is my first project. This is a game. This project is made by C language. 

#include<stdio.h>



int RPS(char player, char computer)
{
if(player==computer) // play draw
return 0;

if(player=='R' && computer=='S') //win player
return 1;
else if(player=='S' && computer=='R') //win computer
return -1;

if(player=='S' && computer=='P') //win player
return 1;
else if(player=='P' && computer=='S') //win computer
return -1;

if(player=='P' && computer=='R') //win player
return 1;
else if(player=='R' && computer=='P') //win computer
return -1;
}
