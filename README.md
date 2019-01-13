####Задания по JavaScript
1. Определите переменные str, num, flag и txt со значениями «Привет», 123, true, «true».
При помощи оператора определения типа убедитесь, что переменных принадлежат типам: string, number, boolean.
2. Создайте переменные a1, a2, a3, a4, a5. При помощи математических операторов (сложение, вычитание и т.д.)
найдите значения выражений:
5 + 3,
5 - 3,
5 * 3,
5 / 3,
поместив результат каждого выражения в соответствующую переменную. Например, let a1 = 5 + 3.
3. Создайте переменные a6, a7, a8, a9, a10. Поместите в них результат выражений:
5 % 3,
3 % 5,
5 + '3',
'5' - 3,
75 + 'кг'
.
4. Напишите скрипт, который находит площадь прямоугольника высота 23см. (в числовую переменную height),
шириной 10см (в числовую переменную width), значение площади должно хранится в числовой переменной s.
5. Напишите скрипт, который находит объем цилиндра высотой 10м (переменная heightC) и диаметром основания 4м (dC),
результат поместите в переменную v.
6. У прямоугольного треугольника две стороны n (со значением 3) и m (со значением 4). Найдите гипотенузу k по теореме
Пифагора (нужно использовать функцию Math.pow(число, степень) или оператор возведения в степень ** ).
7. (*) Найди двенадцатый элемент (let nFib = 12, el12;) последовательности Леонардо Пизанского
(нужно использовать функцию Math.pow(число, степень)). Не забудьте округлить полученное число до целого — Math.round(число).
8. (*) Даны размер ипотечного кредита (S — 2 млн.руб), процентная ставка (p  — 10%), кол-во лет (years — 5).
Найти переплату по кредиту, значение переплаты должно содержаться в переменной perepl.

####JavaScript циклы
1. Создайте переменные m и n. В m поместите произвольное числовое значение. Напишите оператор ветвления if так,
чтобы если m было больше 50, то в переменную n помещалось слово «большое», иначе — слово «маленькое».
2. Определите сколько раз выполнится цикл while? Примечание: это можно сделать прочитав скрипт или запустив его консоли браузера.
var i = 2;
while( i < 9 ){
 console.log( i++ );
}
3. Напишите скрипт, который используя оператор while выведет все числа от 45 до 67.
4. Напишите скрипт, который используя оператор while выведет все числа от 45 до 670, кратные 10.
5. Напишите скрипт, который используя оператор for выполнит два предыдущих задания.
6. Переменная n хранит целое число от 0 до 9. Используя оператор switch, написать скрипт, который
в зависимости от числа будет выводить слово (Например, если n равно 3, то будет выводиться слово «три»)
var n = 5;
switch( n ){
 //ваш код
}
7. Используя document.write() и любую из циклических конструкций выведите  десять одинаковых
изображений (надо выводить <img src="..." alt="..." />)
8. (*) В переменных size и unit хранятся размер и единицы измерения информации 120 и «Кб» соответственно.
Зная что могут быть заданные Кб, Мб, Гб (кило-, мега- и гигабайты) и 1килобайт равен 1024 байта, найти количество байт в size.
9. (*) Постройте при помощи циклов JavaScript скрипт для календаря на HTML. Примечание: выполнить задание
для одного месяца, используя HTML-элемент table

####Функции в JavaScript
1. Напишите функцию hello1(), которая при вызове будет возвращать строку «Привет, JavaScript!».
2. Напишите функцию hello2(), которая при вызове будет принимать переменную name (например, «Василий») и выводить строку 
(в нашем случае «Привет, Василий»).  В случае отсутствующего аргумента выводить «Привет, гость»
3. Напишите функцию mul(n,m), которая принимает два аргумента и возвращает произведение этих аргументов. Проверьте ее работу.
4. Создайте функцию repeat(str, n), которая возвращает строку, состоящую и n повторений строки str. n — по умолчанию 2, 
str — пустая строка
5. Создайте функцию rgb(), которая будет принимать три числовых аргумента и возвращать строку вида «rgb(23,100,134)». 
Если аргументы не заданы, считать их равными нулю. Не проверять переменные на тип данных
6. Создайте функцию avg() , которая будет находить среднее значение по всем своим аргументам (аргументы величины числовые).
7. Создайте функцию m(a,b) оболочку для mul(). m() должна принимать два аргумента а возвращать результат работы mul() 
с этими двумя аргументами После выполнения задания поэкспериментируйте, создайте функцию log(), которая будет принимать одно 
значение, а вызывать  console.log() с этим значением.
8. (*) Напишите функцию operation(m,n,o), в которой m и n — числовые переменные, а o — функциональный литерал, который берет 
два аргумента и выполняет математическую операцию над ними (например, функция mul() из задания 4.)
9. (*) Напишите функцию addN(n), которая вернёт другую функцию. Возвращенная функция должна складывать получаемый аргумент 
с аргументом n возвращающей функции. Внимание, эта простая на реализацию замыкания.
10. (*) Напишите функцию words(),  которая в зависимости от переданного в нее целочисленного аргумента n, будет выводить 
слово «товар» в нужно форме («12 товаров», но «22 товара»). По умолчанию аргумент d должен иметь значение 0

####Задачи на работу с объектами
1. Создайте объект city1 (var city1 = {}), укажите у него свойства name (название города, строка) со значением «ГородN» и 
population (населенность города, число) со значением 10 млн.
2. Создайте объект city2 через нотацию {name: "ГородM", population: 1e6}.
3. Создайте у объектов city1 и city2 методы getName(), которые вернут соответствующие названия городов
4. Создайте методы exportStr() у каждого из объектов. Этот метод должен возвращать информацию о городе в формате 
«name=ГородN\npopulation=10000000\n». Для второго города будет строка со своими значениями. Примечание: можно обращаться 
к каждому свойству через цикл for/in, но методы объекта возвращать не нужно
5. Создайте глобальную функцию getObj(), которая возвращает this. А у каждого из объектов city1 или city2 метод getCity, 
который ссылается на getObj. Проверьте работу метода. Примечание: к объекту вызова можно обратиться через this.
6. (*) Создать объект obj, с методами method1(),method2() и method3(). В методе method3() должна возвращаться строка «метод3». 
Сделайте так, чтобы было возможно выполнение кода obj.method1().method2().method3().
7. Создайте массив d1 с числовыми величинами 45,78,10,3.  Добавьте в массив d1 еще одно число ( d1[7] = 100). 
Выведите в консоль весь массив и его элементы с индексами 6 и 7.
8. Создайте массив d2 с числовыми величинами 45,78,10,3. Посчитайте в переменную sum2 сумму чисел в нем, при помощи цикла for .
9. Создайте массив d3 с числовыми величинами 45,78,10,3. Добавьте в массив d3 еще одно число (например, d[7] = 100) 
Посчитайте в переменную sum3 сумму чисел в нем, при помощи цикла for/in.
10. Создайте массив d4 с числовыми величинами 45,78,10,3. Напишите функцию сортировки my(a,b), которая при вызове d4.sort(my) 
отсортирует элементы массива по убыванию чисел. Вызовите d4.sort(my)
11. (*) Создайте двумерный массив d5 размером n=3 элементов в каждом из которых будет m=4 элементов из целых чисел (в каждый 
элемент поместить цифру 5). Примечание: при создании двумерного массива используйте циклы. 
Во внешнем цикле должна появиться конструкция d5[i] = [];