# Multivariate-statistical-analysis

Лабораторная работа “Число посетителей интернет-магазина” (Numpy 1)

1.   
Сгенерировать данные по посещаемости
интернет-магазина за  n дней
(n=30
- месяц)  — КОЛИЧЕСТВО ПОСЕТИТЕЛЕЙ и
ЧИСЛО ПОКУПОК.  

КОЛИЧЕСТВО ПОСЕТИТЕЛЕЙ – нормально распределенная случайная величина с математическим
ожиданием равным 1000 и ско равным 100 (floor – целое).

ЧИСЛО ПОКУПОК = КОЛИЧЕСТВО ПОСЕТИТЕЛЕЙ//100 (целочисленное деление) плюс целое
случайное число из диапазона (-20,20). 

(Это будут два массива, имена — латиница).

Проверить, если в массивах есть отрицательные значения, обнулить их (два
способа – цикл и фильтрация).

2.   
Найти максимальные и минимальные значения
показателей и распечатать с пояснениями (print) (функции и/или методы).

3.   
Оценить средние, медианы, дисперсии,
стандартные отклонения и распечатать (функции и/или методы).

4.   
Найти коэффициент корреляции (построить корреляционную
матрицу). Есть ли связь между количеством посетителей и числом покупок?

5.   
Выяснить, в какую половину месяца было
больше посетителей (срез+функция/метод+if).

6.    Распечатать
количество посетителей и число покупок для суббот (считаем, что месяц
начинается с понедельника). Два способа — цикл и срезы.

7.    Распечатать
данные о количестве посетителей (фильтрация) для тех дней,
a.    когда
их было больше 1000
b.    когда
их было больше 10, но меньше 100

8.    Переписать
в новый массив информацию о числе посетителей для тех дней, когда покупок не
было (фильтрация). Сколько было таких дней? (размер нового массива).

P.S. (к пункту 8): при фильтрации массива A1 можно
использовать условие для массива A2, если они одного размера и связаны (иначе
смысл теряется). Например:

A1[A2>0] — берутся те элементы массива A1,
которым соответствуют положительные элементы массива A2 (то есть, с теми же индексами).
