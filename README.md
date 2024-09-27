F_num = float(input("Enter first number "))
S_num = float(input("Enter second number "))
print("Choose your operation number")
operation = ["1- Multiplication", "2- Division", "3- Subtraction", "4- Addition"]
for i in range(len(operation)):
    print(operation[i])
oper = int(input())

import os
os.system('cls' if os.name == 'nt' else 'clear')

if oper == 1:
    print(str(F_num) + ' * ' + str(S_num) + ' = ' + str(F_num * S_num))
elif oper == 2:
    print(str(F_num) + ' / ' + str(S_num) + ' = ' + str(F_num / S_num))
elif oper == 3:
    print(str(F_num) + ' - ' + str(S_num) + ' = ' + str(F_num - S_num))
elif oper == 4:
    print(str(F_num) + ' + ' + str(S_num) + ' = ' + str(F_num + S_num))
else:
    print("Error")
