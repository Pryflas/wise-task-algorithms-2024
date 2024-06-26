> Теоретическая справка к модулю **"Количество совершенных паросочетаний в графе"**

**Модуль подготовила: Матеюк Диана Сергеевна 2384**

# Совершенное паросочетание в графе

Совершенным паросочетанием называется паросочетание, в котором участвуют все вершины графа. То есть любая вершина графа инцидентна ровно одному ребру, входящему в паросочетание. Любое совершенное паросочетание является наибольшим и максимальным. Совершенное паросочетание является также рёберным покрытием минимального размера.

Число совершенных паросочетаний в двудольном графе равно перманенту его матрицы смежности.

Алгоритм генерирует матрицу смежности для графа и считает перманент этой матрицы. Функция рекурсивно вычисляет перестановку строк матрицы, умножая соответствующие элементы. Сложность этой функции зависит от количества строк в матрице (O(2^n)), где (n) - количество строк в матрице.
