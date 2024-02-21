
print ("Введите чётные числа от 0 до 20")
for i in range( 0 , 21, 2):
      print (i)
print("Каждое третье число от -1 до -21:")
i = -1 
while i >= -21:
    print(i)
    i -= 3
#2
num = int(input("Введите число для таблицы умножения"))
print(f"Таблица умножения для числа {num}: ")
i = -1
while i <= 10:
      result = num * i
      print (f"{num} * {i}) = {result}")
      i += 1
#3
def fibonacci(n):
    fib_list = [0, 1]
    while len (feb_list) < n:
        fib_list.append(fib_list[-1] + fib_list [-2])
        return fib_list
n = 10
print(fibonacci(n))
