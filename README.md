# MoneyPulator

## Эвристический поиск для роботов-манипуляторов
![Example](https://user-images.githubusercontent.com/35924216/169374960-472e2e6a-b97f-4f20-aed1-474e171deed8.gif)
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
