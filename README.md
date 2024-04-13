SIMPLE SHELL PROGRAMS
Algorithm
Step 1 : Start
Step 2 : Read the values of a and b
Step 3 : Interchange the values of a and b using another variable t as follows: t = a a = b b = t
Step 4 : Print a and b Step 5 : Stop
Program (swap.sh) # Swapping values
echo -n "Enter value for A : " read a echo -n "Enter value for B : " read b t=$a a=$b b=$t
echo "Values after Swapping" echo "A Value is $a" echo "B Value is $b"
Output
[student@krce ~]$ sh swap.sh Enter Value for A:5 
Enter Value for B:6 Values after Swapping A value is 6 B values is 5 [student@krce ~]$
