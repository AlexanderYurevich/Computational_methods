# Cubic spline interpolation
На отрезке $[a, b] = [-2, 2]$ задана функция $f_{1}(x) = \cos(x)$. Требуется:
1. **Вычислить значения функции** в равноотстоящих узлах { $x_{i} = a + ih \mid i = \overline{0, N}, h = (b - a) / N, N = 15$ }.
2. **По полученной таблице** { $x_i, f_1(x_i)$ } построить интерполяционный кубический сплайн $S_{3}(x)$ для функции $f_{1}(x)$.
3. **В узлах $\bar{x_i} = a + i(b - a)/100, i=\overline{0, 100}$** вычислить значения сплайна $S_{3}(x)$ и сравнить со значениями функции
$f_{1}(x)$ в этих узлах, т.е. найти $\max_{i=0,100} |S_3(\bar{x_i}) - f_1(\bar{x_i})|$.
4. **В одной системе координат построить график функции** $f_1(x)$ и график интерполяционного кубического сплайна $S_{3}(x)$. Построить график погрешности интерполирования кубическим сплайном.
# Технологии
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
