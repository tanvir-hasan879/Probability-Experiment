# Probability-Experiment

import random
number = int(input("Enter how may time you want to experiment :"))
count = 0
Theoretical_value = (1/6) * 100

dice_number = random.randint(1,6)
for i in range(0,number):
    dice_number = random.randint(1,6)

    if dice_number == 5 :
        count += 1

Practical_value = (count/number)*100
Result_difference = (Practical_value/Theoretical_value)*100        
        
print("Practical value:", Practical_value)
print("Theoretical value:", Theoretical_value)
print("Comparision:", Result_difference)


        
        
