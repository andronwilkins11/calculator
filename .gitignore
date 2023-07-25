def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "На ноль делить нельзя!"

def average(numbers):
    return sum(numbers) / len(numbers)

def calculator():
    print("Выберите операцию:")
    print("1. Сложение")
    print("2. Вычитание")
    print("3. Умножение")
    print("4. Деление")
    print("5. Найти среднее значение списка чисел")
    print("0. Выход")

    while True:
        choice = input("Введите номер операции: ")

        if choice == '0':
            print("Выход из калькулятора.")
            break

        if choice in ('1', '2', '3', '4'):
            num1 = float(input("Введите первое число: "))
            num2 = float(input("Введите второе число: "))

            if choice == '1':
                print("Результат:", add(num1, num2))
            elif choice == '2':
                print("Результат:", subtract(num1, num2))
            elif choice == '3':
                print("Результат:", multiply(num1, num2))
            elif choice == '4':
                print("Результат:", divide(num1, num2))

        elif choice == '5':
            num_list = [float(num) for num in input("Введите числа через пробел: ").split()]
            print("Среднее значение:", average(num_list))

        else:
            print("Некорректный ввод. Пожалуйста, выберите правильный номер операции.")

if __name__ == "__main__":
    calculator()
