#!/bin/bash

#this is a for loop for BIOL432 assignment 4
# this for loop counts from 1-20 and prints whether the number is a 
single or double digit 

for Count in {1..20}
do
if [ $Count -lt 10 ]
then
 echo "$Count is a single-digit number"  
else 
 echo "$Count is a double-digit number"
fi
done 
