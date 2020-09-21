# Домашнее задание
## Двоичное дерево поиска, АВЛ и Декартово дерево
 
Цель: Создать двоичное дерево поиска, реализовать один из вариантов балансировки.
Сравнить эффективность алгоритмов на случайных и упорядоченных данных.
1 часть, обязательная. 5 байтов.
Создать простейшее двоичное дерево поиска. +3 байта.
Методы к реализации:
void insert(int x) - вставка элемента
bool search(int x) - поиск элемента
void remove(int x) - удаление элемента

Протестировать работу алгоритма. +1 байт.
Создать два дерева (максимальный размер дерева выберите такой, чтобы программа работала не дольше 1 минуты)
Добавить N чисел в случайном (первое) и возрастающем (второе) порядке.
Искать N/10 случайных чисел в каждом дереве.
Удалить N/10 случайных элементов в каждом дереве.

Заполнить таблицу производительности и сделать вывод. +1 байт.
Написать, сколько потребовалось времени.

2 часть, на выбор. 5 байтов.
Расширить класс из 1 части и создать сбалансированное АВЛ-дерево. +4 байта.
Методы к реализации:
smallLeftRotation(Tree t) smallRightRotation(Tree t) - малое левое/правое вращение
bigLeftRotation(Tree t), bigRightRotation(Tree t) - большое левое/правое вращение, написать через вызов малых вращений
(при желании выполнить оптимизацию: переписать через прямые присваивания и проверить эффективность)
void insert(int x) - вставка элемента
void remove(int x) - удаление элемента
void rebalance(Tree t) - перебалансировка дерева

Протестировать работу алгоритма аналогичным образом,
дополнить таблицу производительности, сделать вывод +1 байт.
Написать, сколько потребовалось времени.

3 часть, на выбор. 5 байтов.
Расширить класс из 1 части и создать декартово дерево. +4 байта.
Методы к реализации:
Tree merge(Tree l, Tree r) - объединение двух деревьев
void split(Tree t, int x, out Tree l, out Tree r) - разделение дерева на две части
void insert(int x) - добавление элемента
void remove(int x) - удаление элемента
Протестировать работу алгоритма аналогичным образом,
дополнить таблицу производительности, сделать вывод +1 байт.
Написать, сколько потребовалось времени.

При необходимости вы можете изменить заголовки методов.
Критерии оценки: +5 байтов за реализацию простейшего двоичного дерева поиска с тестированием и выводом
+5 байтов за реализацию АВЛ-дерева с тестированием и выводом
+5 байтов за реализацию Декартово дерева с тестированием и выводом