# Гаврюхин А.В._Java

### Тестовое задание для стажера AQA

* Тестовое задание выполнено на Java 11 в Intelleji Idea 
* Последний раздел - задание со скобочной последовательностью.

**scr/Main.java содержит все три задания.**

При запуске последовательно выполняются первых 3 задания:

1. Составить алгоритм: если введенное число больше 7, то вывести “Привет”

2. Составить алгоритм: если введенное имя совпадает с Вячеслав, то вывести “Привет, Вячеслав”, если нет, то вывести "Нет такого имени"

3. Составить алгоритм: на входе есть числовой массив, необходимо вывести элементы массива кратны 3

4. Задание, ответ в текстовой форме:
Дана скобочная последовательность: [((())()(())]]
Можно ли считать эту последовательность правильной?  
Если ответ на предыдущий вопрос “нет” - то что необходимо в ней изменить, чтоб она стала правильной?

Ответ:
Приведенная последовательность неправильная.

Для приведения к правильной скобочной последовательности необходимо:

уровнять количество скобок соответствующих типов противоположными скобками (для сободной открывающей добавить закрывающую, и на оборот)
или заменить непарные скобки скобками одного типа  
* Например:  [ ( (()) () (()) ) ] заменили непарную закрывающую скобку ] скобкой ) (предпоследний символ) 