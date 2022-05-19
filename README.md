# MoneyPulator

## Эвристический поиск для роботов-манипуляторов
![file_2](https://user-images.githubusercontent.com/35924216/169374028-2ee4684a-0e28-4548-a5bf-b83c6fdd0bf9.gif)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMiknich/MoneyPulator/blob/main/Manipulator.ipynb)

В данном репозитории представлен базовый алгоритм эвристического поиска A* для плоского n-шарнирного манипулятора.


Параметры эксперимента задаются внутри `stationary_test()`:
- `height` --- высота среды
- `width` --- ширина среды
- `d_theta` --- шаг по углу для каждого узла манипулятора
- `manipulator_ls` --- длины сочленений манипулятора
- `manipulator_thetas` --- начальное положение манипулятора (углы каждого сочленения)
- `starts` --- набор начальных точек (точка крепления манипулятора)
- `goals` --- набор целевых точек
- `objects` --- множество стационарных круглых препятствий заданных центрами и радиусом
