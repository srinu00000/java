def is_composite(num):
    if num <= 1:
        return False
    if num <= 3:
        return False
    if num % 2 == 0 or num % 3 == 0:
        return True
    i = 5
    while i * i <= num:
        if num % i == 0 or num % (i + 2) == 0:
            return True
        i += 6
    return False
def print_composite_numbers(a, b):
    composites = []
    for num in range(a, b + 1):
        if is_composite(num):
            composites.append(num)
    return composites
# Sample Input
A = 12
B = 19
# Print Composite Numbers
composite_numbers = print_composite_numbers(A, B)
print(", ".join(map(str, composite_numbers)))
