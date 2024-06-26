Название модуля: Граф является 4-раскрашиваемым.

Теория:

Граф - это структура, представляющая собой набор объектов, в которых некоторые пары объектов в некотором смысле "связаны". Объекты представлены абстракциями, называемыми вершинами (также называемыми узлами или точками), и каждая из связанных пар вершин называется ребром (также называемым связующим звеном или линией). Обычно граф изображается в схематической форме в виде набора точек или окружностей для вершин, соединенных линиями или кривыми для ребер.

Поиск в глубину (англ. Depth-first search, DFS) — один из методов обхода графа. Стратегия поиска в глубину, как и следует из названия, состоит в том, чтобы идти «вглубь» графа, насколько это возможно. Алгоритм поиска описывается рекурсивно: перебираем все исходящие из рассматриваемой вершины рёбра. Если ребро ведёт в вершину, которая не была рассмотрена ранее, то запускаем алгоритм от этой нерассмотренной вершины, а после возвращаемся и продолжаем перебирать рёбра. Возврат происходит в том случае, если в рассматриваемой вершине не осталось рёбер, которые ведут в нерассмотренную вершину.

K-раскрашиваемый граф — граф, хроматическое число которого не превосходит K. То есть его вершины можно раскрасить не более чем K цветами так, что у любого ребра концы будут разного цвета.

Хроматическое число графа - минимальное число цветов, в которые можно раскрасить вершины графа так, чтобы концы любого ребра имели разные цвета.

Алгоритм решающий задачу: в цикле запускается dfs из каждой вершины до каждой, вершины нумеруются в соответствии с их цветом, запоминается максимальный номер. Это хроматическое число. Если хроматическое число меньше или равно 4, то алгоритм возвращает true. 
