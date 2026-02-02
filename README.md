# convert-decimal-number-to-an-equivalent-binary-number.
def decimalToBinary(num):
    """This function converts a decimal number to binary"""
    if num > 1:
        decimalToBinary(num // 2)
    print(num % 2, end='')


number = int(input("Enter any decimal number: "))
decimalToBinary(number)
