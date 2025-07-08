# Rhombix-task-1
def Fibonacci_series(n):
       fib=[0,1]
       for i in range(2,n):
          fib.append(fib[i-1]+fib[i-2])
       return fib
n=10
print("Fibonacci series upto ", n)
print(Fibonacci_series(n))
