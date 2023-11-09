def fibonacci(n):
  if n <= 0:
      return "Invalid input"
  elif n == 1:
      return [0]
  elif n == 2:
      return [0, 1]
  else:
      sequence = [0, 1]
      while len(sequence) < n:
          sequence.append(sequence[-1] + sequence[-2])
      return sequence

def main():
  n = int(input("Enter a number: "))
  result = fibonacci(n)
  print("Fibonacci sequence:", result)
