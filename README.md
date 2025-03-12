def check_number(num):
    if num % 2 == 0:
        print(f"{num} Even number po kuya.")
    else:
        print(f"{num} Odd number po bes.")


print("iCheck natin kung Odd or Even numbers ang lalabas!")

try:
    glenn = int(input("baby pili ka kahit anong number mo: "))
    check_number(karl)  
except ValueError:
    print("ayaw naman baby number lang dapat.")
