# Инструкция для работы с Git

* git init инициализация локального репозитория
* git status получить информацию о текущем состоянии репозитория
* git  add добавить файл или файлу к следующему коммиту
* git commit -m "фиксация изменений и создание комментария"
* git log вывод на экран историю всех коммитов с их хэш - кодами для текущего репозитория
* git checkout 1234 переход к коммиту, где 1234 - первые символы хэш кода
* git checkout master переход в актуальную версию ветки master
* git diff просмотреть разницу между текущим и закоммиченным файлом

* clear очистить терминал

* git branch - создание новой ветки

* git merge - название ветки, которую мы хотим "залить" в текущую ветку

Цитата: Для всего, что сохраняется в Git, сначала вычисляется контрольная сумма, и в дальнейшем она же и используется для поиска содержимого.

Цитата: Git хранит данные не как последовательность изменений или дельт, а как последовательность снимков состояния (snapshot)

Цитата: Как только вы отредактируете файлы, Git будет рассматривать их как изменённые, т.к. вы изменили их с момента последнего коммита

![Тайланд](Thailand_KoLan.jpg)

Это Тайланд

Цитата: Стандартный рабочий процесс с использованием Git'а выглядит примерно так:
Вы вносите изменения в файлы в своём рабочем каталоге.
Подготавливаете файлы, добавляя их слепки в область подготовленных файлов.
Делаете коммит, который берёт подготовленные файлы из индекса и помещает их в каталог Git'а на постоянное хранение

# Домашняя работа 2

https://learngitbranching.js.org/?locale=ru_RU это онлайн учебник по git/

В нем есть неизвестные нам команды

+ cherry-pick
+ reset
+ revert
+ rebase

rebase показалась мне очень удобной командой. Она выстраивает коммиты по порядку. Это удобно когда много веток.


Относительные ссылки - удобный инструмент перемещения между коммитами.

С помощью оператора каретки можно перемещаться на один или несколько коммитов назад.
На Лекции 3 мы изучали GitHub

Новые команды из GitHub

+ git push
+ git pull
+ git clone
+ git fork

## Еще команды git

+ git archive
+ git show
+ git grep
+ git blame

Результат матча Германия - Япония 1:2

# Итого в домашнем задании

1. Создана ветка Homework_2
2. Созданы еще 3 ветки, в которые заносились команды git
3. Затем информация из этих веток была поочередно слита в ветку Homework_2 без конфликтов
4. Для показания слияния с конфликтом созданы ветки football_1  и football_2. В них была занесена информация о результате футбольного матча, которая при слиянии этих веток вступала в конфликт. Он был разрешен в пользу ветки football_2

5. Были объединены ветки Homework_2 и Master

6. Все ветки кроме Master были удалены.

7. Сделан финальный коммит

# Домашнее задание 3

1. Создана ветка git_instruction

2. В нее внесены начальные сведения и основные команды для начала работы в GitHub

3. Выполнено слияние веток. Инструкция перенесена на ветку Master




## Краткая инструкция по работе с удаленными репозиториями

1. Сервис GitHub от Microsoft предоставляет возможность работать с удаленными репозиториями.

2. Для начала работы следует создать аккаунт на GitHub


3. После этого можно забирать находящиеся на GitHub репозитории на свой компьютер и отправлять свои репозитории или свои изменения в скачанном репозитории назад на GitHub.

## Основные команды для работы с Git Hub

- git clone [ссылка на репозиторий] - скачиваем удаленный репозиторий на свой компьютер

- git push - отправляем свой репозиторий на GitHub

- git pull - забираем на свой компьютер изменения, сделанные на GitHub

- fork (вводится на GitHub в своем аккаунте) - копировать произвольный репозиторий на свой аккаунт для дальнейшей работы с ним.

- pull request - запрос владельцу репозитория на просмотр внесенных локально или в своем аккаунте изменений