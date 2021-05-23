# Лабораторна робота 3
## Тема: _Методи обходу та модифікації графів_
## Мета роботи: _Навчитись застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева_

## Хід роботи
У роботі використовується онлайн ресурс для генерування графів [Graph Online](https://graphonline.ru/).
1. За допомогою лабораторного макету побудувати випадковий неорієнтований граф `G={8,12}`:
   ![граф](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/gr1%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA.PNG?raw=true)
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS); (для 2-х різних вершин)

   ![граф](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/lab%203.1.jpg?raw=true)
    1. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?

   **Відповідь: Ні. Різна кількість ребер.**

    1. Побудувати дерево за алгоритмом обходу в глибину (DFS); (для 2-х різних вершин)

   ![граф](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/lab3.2.jpg?raw=true)

    1. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?

   **Відповідь: Ні.**

1. За допомогою лабораторного макету побудувати випадковий орієнтований граф `G={6,10}`:
   ![граф](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/gr2.PNG?raw=true)
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS);

   ![граф](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/33.1.jpg?raw=true)

    1. Яка вершина (вершини) буде знайдена останньою?

   **Відповідь: вершина 5, 4**

    1. Визначити чи існують цикли. Вказати послідовність ребер і їх довжину.

   **Відповідь:**
   **5, 3, 4, 5. Довжина 3.**

    1. Визначити кількість хвиль, які пройдуть по ребрах доки буде виявлена остання вершина.

   **Відповідь: 2 хвилі**

    1. Побудувати дерево за алгоритмом обходу в глибину (DFS);

   ![граф](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/34d2961871-6de5-4c13-ac55-a1a7314f465f.jpg?raw=true)

1. Побудувати дерево шляхів рангом `r=4` для випадкового графа `G={6,9}`.

![alt text](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/3.4gr%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA.PNG?raw=true)

![alt text](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/35.jpg?raw=true)

1. Побудувати мінімальне зв’язне дерево для графа `G`. Вказати його вагу.

![alt text](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/36%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA.PNG?raw=true)

![alt text](https://github.com/SavrunYura/savryn_lab_totk_2021/blob/main/%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D1%8F3/36d4adb600-0d08-4391-9a16-19ea86e67538.jpg?raw=true)


**Відповідь: Вага = 29**
