# Project-5
def fibonacci(n):
    if n <= 1:
        return n
    else:
        return fibonacci(n-1) + fibonacci(n-2)

for i in range(1, 9):
    print(fibonacci(i))

def reverse_string(s):
  return s[::-1] 
input_string = "amin"
reversed_string = reverse_string(input_string)
print(reversed_string)
