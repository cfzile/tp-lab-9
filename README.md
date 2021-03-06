
<img src="img/green.png" width="50" height="50">

# Cpp-lab-9

## Практикум №9 (Функциональное и многопоточное программирование)

### Задание 1.

> Написать функцию сортировки строк методом пузырька. Сравнение двух соседних элементов в функции должно осуществляться с помощью лямбда-выражения, которое передается в функцию в виде параметра. Составить пример использования сортировки, используя не менее 5 разных функций-компараторов.

### Задание 2.

> Написать программу, в которой для сортировки массива строк из 1 задачи применяется отдельный поток (std::thread). Сортировка происходит во вспомогательном потоке, а основной поток выводит содержание массива после каждого шага алгоритма. Потоки должны использовать мьютексы для синхронизации работы.

### Задание 3.

> Написать программу, которая моделирует обслуживание покупателей в супермаркете. Идея задачи состоит в том, что покупатели подходят к кассам в случайные моменты времени и с тележками, содержащими случайное количество продуктов (std::vector). Для обслуживания нескольких покупателей (до 5 человек) создается очередь (std::queue). Покупатели ставятся в конец очереди. Как только очередь заполняется для одной кассы, создается новый поток-касса со своей очередью. Поток-касса может завершить выполнение, если покупатели заканчиваются. Процесс обслуживания покупателя заключается в переборе всех продуктов, представляемых целыми числами в векторе с небольшой задержкой. 


 
## Список участников/веток

|  ФИО              | Имя ветки |
|-------------------|-----------|
|Альперович	Вадим | b1|
|Андрющенко	Александр|b2|
|Аросланкин	Артем|b3|
|Востряков	Дмитрий|b4|
|Горбачева	Арина|b5|
|Горшкова	Екатерина|b6||
|Доненко	Денис|b7|
|Исупова	Мария|b8|
|Кислицына	Анастасия|b9|
|Куклин	Максим|b10|
|Лесин	Николай|b11|
|Макридин	Максим|b12|
|Максимов	Антон|b13|
|Малинин	Василий|b14|
|Мартиросян	Елизавета|b15|
|Мурзаев	Роман|b16|
|Сазанов	Дмитрий|b17|
|Седунов	Илья|b18|
|Сиднева	Анастасия|b19|
|Ситникова	Владислава|b20|
|Слесарева	Василина|b21|
|Смольникова	Полина|b22|
|Тюлин	Владислав|b23|
|Филиппова	Марина|b24|
|Черноземова	Дарья|b25|
|Чернышев	Константин|b26|
|Черняев	Ярослав|b27|
|Втюрин Павел|b28|
|Славутин Александр|b29|
|Семкин Павел|b30|

## Алгоритм выполнения работы

Для выполнения работы необходимо:

1. Выполнить *fork* репозитария в свой аккаунт.
1. Выполнить клонирование репозитария из своего аккаунта к себе на локальную машину (`git clone`).
1. Создать ветку **git** с индивидуальным номером (`git branch имя_ветки`).
1. Сделать ветку активной (`git checkout имя`).
1. Необходимо разместить как исходные файлы с решениями задач, поместив **cpp** файлы в **src**, а заголовочные - в **include**. 
1. Добавить файлы в хранилище (`git add`).
1. Выполнить фиксацию изменений (`git commit -m "комментарий"`).
1. Отправить содержимое ветки в свой удаленный репозитарий (`git push origin имя_ветки`).
1. Создать пул-запрос в репозитарий группы и ждать результата от **Travis-CI**.

