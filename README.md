# one
def check_even_odd(number):
    if number % 2 == 0:
        return f"{number} is even."
    else:
        return f"{number} is odd."

# Test the function
test_number = 10
result = check_even_odd(test_number)
print(result)
