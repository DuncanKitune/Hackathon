def generate_fibonacci(n):
    fibonacci_sequence = [0, 1]
    
    while fibonacci_sequence[-1] + fibonacci_sequence[-2] <= n:
        next_fibonacci = fibonacci_sequence[-1] + fibonacci_sequence[-2]
        fibonacci_sequence.append(next_fibonacci)
    
    return fibonacci_sequence

# Example usage:
n = int(input("Enter the value of n: "))
fibonacci_sequence = generate_fibonacci(n)
print("Fibonacci sequence up to", n, ":", fibonacci_sequence)

age= int(input("Enter your current age"))

if age >= 18:
    print("You are eligible to vote.")
else:
    print("You re not eligible to vote.")
