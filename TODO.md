number = int(input("正の整数を入れてね: "))

if number % 15 == 0:
    print("FizzBuzz")

if number % 3 == 0:
    print("Fizz")

if number % 5 == 0:
    print("Buzz")

print(number)

$ python app.py
1
2
Fizz
4
Buzz
# 省略
14
FizzBuzz
16
# 省略
99
Buzz

