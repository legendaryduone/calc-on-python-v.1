import math
while True:
    print('Добро пожаловать в рандомный калькулятор!')
    print('---')
    print('Если собираетесь искать корень, то вводите только первое число. Второе можете выбрать любым')
    print('---')
    num_1 = float(input('Введите первое число с которым хотите произвести операцию: '))
    num_2 = float(input('Введите второе число с которым хотите произвести операцию: '))

    text = str(input('Введите вашу операцию ( + - * ** / // % swrt ): '))

    if text == '+':
        print('Результат: ', num_1 + num_2)
    elif text == '-':
        print('Результат: ', num_1 - num_2)
    elif text == '*':
        print('Результат: ', num_1 * num_2)
    elif text == '**':
        print('Результат: ', num_1 ** num_2)
    elif text == '/':
        if num_2 == 0:
            print('На ноль делить нельзя')
        else:
            print('Результат: ', num_1 / num_2)
    elif text == '//':
        print('Результат: ', num_1 // num_2)
    elif text == '%':
        print('Результат: ', num_1 % num_2)
    elif text == 'sqrt':
        print('Результат: ', math.sqrt(num_1))
    else:
        print('Неизвестная операция, попробуйте еще раз!')
        print('---')
        continue
    again = input('Хотите посчитать еще что-то? Да или Нет?: ').lower()
    if again != 'да':
        print('---')
        print('Спасибо, что воспользовались нашим калькулятором')
        break
