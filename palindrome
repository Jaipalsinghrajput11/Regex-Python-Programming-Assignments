def is_palindrome(number):
    number_str = str(number)
    for i in range(len(number_str) // 2):
        if number_str[i] != number_str[len(number_str) - i - 1]:
            return False
    return True
num = 12321
if is_palindrome(num):
    print(f"{num} is a palindrome.")
else:
    print(f"{num} is not a palindrome.")
