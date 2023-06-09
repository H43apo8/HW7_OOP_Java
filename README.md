# Объектно-ориентированное программирование
## Урок 7. ООП Дизайн и Solid ч.2
### Практическая работа №7:  
    Создать проект калькулятора комплексных чисел (достаточно сделать сложение, умножение и
    деление). Применить при создании программы архитектурные паттерны, добавить
    логирование калькулятора. Соблюдать принципы SOLID, паттерны проектирования.
    
### Решение:
    В методе main мы создаем комплексные числа num1 и num2. Затем создаем объект ConsoleLogger, 
    который будет использоваться для логирования действий калькулятора. Далее создаем объект Calculator 
    с операцией сложения и передаем ему выбранную операцию и логгер.

    Мы выполняем операцию сложения, вызывая метод calculate у объекта calculator, передавая ему комплексные 
    числа num1 и num2. Результат операции сохраняется в переменной sum, а затем выводится в консоль.

    Аналогично мы выполняем операции умножения и деления, создавая новые экземпляры Calculator с соответствующими 
    операциями и вызывая метод calculate.

    Таким образом, код реализует калькулятор комплексных чисел с использованием архитектурных паттернов, принципов 
    SOLID и паттернов проектирования. Логирование осуществляется с помощью логгера ConsoleLogger, который использует 
    стандартный java.util.logging.Logger.
