Сlustering-Set-React

Основная логика приложения представляет собой структуру нейронной сети с выходным слоем Кохонена, выполняющую
кластеризацию множества образов (X1,X2,...Xn) на заданное число кластеров (центроидов -- С1,C2,..,Cn)

Состояние 1 -- необходимо ввести входное множество образов.

Пример входного множества образов (векторов): 
(22,19,7), (16,25,24), (23,17,5), (18,23,17), (21,5,2), (24,8,5), (5,21,3),
(4,19,6), (2,24,8), (23,26,19), (6,20,4), (21,20,2), (18,24,3), (22,25,21),
(19,24,2), (21,3,5), (25,25,24), (20,3,7), (7,18,5), (23,22,21), (8,17,2),
(18,24,3), (22,2,1), (18,3,1), (24,18,6)
![Alt text](/scrin/scrin_1.JPG?raw=true "Optional Title")
Состояние 2 -- произошел ввод входного множества образов (множество отобразилось в виде таблицы, каждый столбец -- один вектор).

Теперь можно провести кластеризацию заданного множества образов для разного числа кластеров и разных скоростей обучения.
Также можно нормализовать входное множество образов.
![Alt text](/scrin/scrin_2.JPG?raw=true "Optional Title")
Состояние 3 -- вывод результата кластеризации входного множества
![Alt text](/scrin/scrin_3.JPG?raw=true "Optional Title")
