
# Bash Script for Generating Multiplication Table 

This Bash script generates a multiplication table for a number entered by the user. 
The script prompt user to enter a number and then ask if they prefer to see a full multiplication table from 1 to 10. Based on the user's choice, the script will display the corresponding multiplication table. 


The script ask the user to input a number for which the multiplication table will be generated. 

#!/bin/bash

# Input from user
echo "Enter the number -"
read n

# initializing i with 1
i=1
  
# Looping i, i should be less than
# or equal to 10 
while [ $i -le 10 ]
do
res=`expr $i \* $n`

# printing on console
echo "$n * $i = $res"
 
# incrementing i by one  
((++i))
  
# end of while loop  
done

<img width="425" alt="mult-tabel" src="https://github.com/danielddu/bash_multi_table/assets/169099038/4591e9e7-5248-4db5-8b52-d342b077dd1f">

# If the user chooses a partial table, Here is a bash script that prompts the user for input:

<img width="597" alt="1 enter" src="https://github.com/danielddu/bash_multi_table/assets/169099038/8874e226-4633-4643-8a26-f18406e0b7ee">


<img width="489" alt="2 output-partial" src="https://github.com/danielddu/bash_multi_table/assets/169099038/8d86515b-a4fb-4261-9eba-a477ae7c80f6">

# Handling Invalid Range
If the user enters and invalid range, Here is a bash script that handles invalid ranges and displays the full table instead:

<img width="641" alt="3 invalid-range-code" src="https://github.com/danielddu/bash_multi_table/assets/169099038/e1e78d92-07c7-4fbb-83bb-442a6f969ca0">
<img width="529" alt="3 invalid-range-output" src="https://github.com/danielddu/bash_multi_table/assets/169099038/084d4ef0-b573-4569-b030-2751162d44b7">




