# lesson64-65
Болкарева Анна

1-Сортировка это расстановка элементов массива в заданном порядке

2-Метод пузырька (сортировка обменами) - название этого метода произошло от известного физического явления пузырёк воздуха в воде поднимается вверх. Если говорить о сортировке массива, сначала поднимается «наверх» (к началу массива) самый «лёгкий элемент (элемент с минимальными значениями), затем следующий и т. д. Метод выбора - ещё один популярный простой метод сортировки метод выбора, при котором на каждом этапе выбирается минимальный элемент (из оставшихся) и ставится на свое место

3-Вложенные циклы используются в алгоритмах сортировки для обработки и сравнения элементов внутри коллекции данных. Основная цель вложенного цикла в алгоритме сортировки состоит в том, чтобы упорядочить элементы в правильной последовательности

4-Меньше всего перестановок будет в выборе, и это очевидно: там при перестановке элемент становится на свое место и больше не перемещается, а вот при пузырьке такие обмены идут постоянно, чтоб элемент стал на свое место , может потребоваться n перестановок

5-Быстрая сортировка - это алгоритм, который состоит из трёх шагов. Сначала из массива нужно выбрать один элемент — его обычно называют опорным. Затем другие элементы в массиве перераспределяют так, чтобы элементы меньше опорного оказались до него, а большие или равные — после

6-Чтобы изменить порядок сортировки столбцов, выберите запись, а затем щелкните стрелку ВВЕРХ или ВНИЗ рядом с кнопкой Параметры , чтобы изменить порядок. Столбцы с более высокой позицией в списке будут отсортированы раньше, чем столбцы с более низкой позицией

7-Да, метод «быстрой сортировки» можно использовать для символьных строк. Однако, при сравнении символьных строк необходимо учитывать их кодировку, что может привести к нежелательным результатам

8-Скорость «быстрой сортировки» зависит от нескольких факторов, включая количество элементов для сортировки, начальное расположение элементов, а также выбранный алгоритм разделения (например, выбор опорного элемента). В среднем случае, «быстрая сортировка» имеет сложность O(n log n), что делает ее одним из самых быстрых алгоритмов для сортировки больших наборов данных. 

Самый лучший случай для «быстрой сортировки» происходит, когда массив элементов уже упорядочен (или близок к упорядоченному), что делает процесс сортировки быстрым и эффективным. Самый худший случай происходит, когда массив элементов разбивается на две равные части, каждая из которых содержит только один элемент. Это добавляет большое количество итераций к процессу сортировки, что замедляет скорость работы алгоритма. Однако, вероятность того, что это произойдет существенно уменьшается при использовании случайного выбора опорного элемента

9-Да, метод быстрой сортировки может работать дольше, чем метод выбора, в определенных условиях, хотя быстрая сортировка, как правило, более эффективна и быстрее, чем сортировка методом выбора, в определенных условиях она может быть менее эффективной и работать дольше

#65

1-Т.к. двоичный поиск заключается в том, что на каждом шаге множество объектов делится на две части и в работе остаётся та часть множества, где находится искомый объект

2-чтобы оценить количество шагов алгоритма двоичного поиска, нужно просто вычислить логарифм размера массива по основанию 2
