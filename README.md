 # Контрольное задание:

**1.** Создать репозиторий на GitHub

**2.** Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)

**3.** Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)

**4.** Написать программу, решающую поставленную задачу

**5.** Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)


## Задача

 Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.



**Примеры:**

**[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]**

**[“1234”, “1567”, “-2”, “computer science”] → [“-2”]**

**[“Russia”, “Denmark”, “Kazan”] → []**



## Алгорим решения:


Задаем два массива строк одинаковой длинны: исходный и еще один массив такой же длинны (т.к. второй массив заполняется элементами из первого/исходного, значит длина его не может быть больше длины первого).

Пишем и применяем метод void, который в введенным в него массиве проверяет число символов каждого отдельного элемента. В метода используем цикл if и переменную count, которая отбирает элементы, отвечающие заданному условию (длинна <= 3) и присваивает их значения элементам второго массива в порядке очереди. Цикл if ограничен длинной массива; переменная count соответствует индексу "заполняемого" элемента второго массива; i увеличивается на 1 при каждом цикле; count увеличивается на 1 только после успешного присвоения значения элементу второго массива.

Пишем и применяем метод void для печати массива в консоль терминала.


## Переменные, интегрированные в код программы (для проверки):

1. Длина исходного массива
2. Элементы массива в формате: {"1223", "1567", "-2", "computer science"}