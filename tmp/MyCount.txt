#!/bin/bash

for Count in {1..20}
do
	echo "$Count"
if [ $Count -lt 10 ]
then
	echo " is a single digit number"
else
	echo "is a double digit number"
fi
done
