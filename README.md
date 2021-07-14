# Final-project-edge2021
# Haya Calculator:
def addition(x, y: object):
    return x + y


def subtraction(x, y: object):
    return x - y


def multiplication(x, y: object):
    return x * y


def division(x, y: object):
    return x / y


print("Select operation.")
print("1.+")
print("2.-")
print("3.×")
print("4.÷")

Select = input("Enter numbers(1/2/3/4):")
Number_1 = int(input("First Number: "))
Number_2 = int(input("Second Number: "))

if Select == "1":
    print(Number_1 + Number_2)
elif Select == "2":
    print(Number_1 - Number_2)
elif Select == "3":
    print(Number_1 * Number_2)
elif Select == "4":
    print(Number_1 / Number_2)
else:
    print("Error")
