# Звіт із лабораторної роботи №3
## Тема: Методи обходу та модифікації графів.
## Мета роботи: Навчитись застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева.
### Виконання роботи
**1.** Побудовано неорієнтований граф G = {8,12}:

![граф G](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/1.png)

**i.** Побудувано дерево за алгоритмом обходу в ширину (BFS) для вершини 1:

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/2.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/2_1.png)


для вершини 5:

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/3.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/3_1.png)


**іі.** Топології дерев побудованих з різних кореневих вершин будуть різними. Це пояснюється тим, що алгоритм обходить не всі ребра графу, відповідно якщо у графі є вершини які мають більше трьох суміжних вершин, то тополігї дерев побудованих з різних кореневих вершин будуть різними.

**ііі. Побудувано дерево за алгоритмом обходу в глибину (DFS);**
з вершини 1:

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/4.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/4_1.png)


з вершини 6:

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/5.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/5_1.png)


**iv.** Топології будуть різними. Це можна пояснити тим, що на кожному кроці алгоритм випадково  знаходить лише одну вершину( випадково вибираючи одну з тих, що до неї під'єднані).

**2.** Побудувано випадковий орієнтований граф `G={6,10}`:

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/6.png)

**i.** Побудувано дерево за алгоритмом обходу в ширину (BFS), починаючи з третьої вершини:

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/7.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/7_1.png)

Порядок обходу: 3 ->2->5->1->6->4

**ii.** Якщо починати обхід графу за алгоритмом обходу в ширину  з третьої вершини, то останньою буде знайдена вершина № 4.

**іii.**  Граф не містить циклів Ейлера та Гамільтона.

**іv**  для виявлення останньої вершини потрібно три хвилі.


**v.** Дерево за алгоритмом обходу в глибину (DFS):

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/8.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/8_1.png)

**3.**  Побудувати дерево шляхів рангом  `r=4`  для випадкового графа  `G={6,9}`.
граф G:

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/9.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/9_1.png)

**4.** Побудувати мінімальне зв’язне дерево для графа G. Вказати його вагу.

![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/10.png)
![enter image description here](https://github.com/RuslanchikB/-Borsuk_Ruslan_LAB_TOTK_2021/blob/main/lab_3/photo/10_1.png)

Вага-> 5+7+9+3+5=29


###Висновок:
Навчився застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева
