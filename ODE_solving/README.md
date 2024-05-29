# ODE solving
- **Решить задачу Коши** на отрезке $[a, b] = [1, 2]$ с шагом $h = 0.1$ неявным методом трапеций,
явным методом средних прямоугольников, предиктор-корректорным методом Адамса 2-го порядка.<br>$u' = -\frac{u}{x}ln(\frac{u}{x}), u(1) = 1$ 
- **Оценить погрешность** численного решения с шагом $h = 0.1$ с помощью правила Рунге (для одношаговых методов). 
- **Сравнить полученные численные решения** с точным решением $u(x)$.
- **В одной системе координат построить** график функции $u(x)$ и график одного из полученных
численных решений.
- **Результаты вычислительного эксперимента оформить** в виде таблицы:

| $i$ | $x_{i}$ | Точное решение<br>$u(x_{i})$ | Метод 1<br>$y_{i}$                        | Метод 2<br>$y_{i}$ | Метод 3<br>$y_{i} |
|-------|---------|---------------------------|------------------------------------------|-----------|-----------|                        
|<p style="text-align: center;"> 0</p>     |         |                           |                                          |           |           |
| <p style="text-align: center;"> ...</p>  |         |                           |                                          |           |           |
| <p style="text-align: center;"> $N$</p> |         |                           |                                          |           |           |
| $\max_{i=0,N} \mid u(x_{i}) - y_{i}\mid$ |                           |                                          |           |           |
| Оценка погрешности по правилу Рунге |  |  |  |  | - |
# Технологии
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
