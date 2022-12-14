# Основные команды GIT

1. _Git init_ - примененная в текущей папке указывает что данная папка будет отслеживаемым репозиторием. При инициализации в ней будет создана скрытая папка, в которой содержатся объекты и ссылки, используемые Git.
2. _Git add "имя файла с расширением"_ - добавляем отслеживаемый файл
3. _Git commit -m "содержание добавлений"_ - сохраняем файл с заметкой что именно мы в него добавили
4. _Git status_ - показывает статус текущего репозитория
5. _Git log_ - отображает список коммитов
6. _Git branch "имя новой ветки" - создаст новую ветку
7. _Git branch_ - просмотр списка веток, при этом текущая будет отмечена (*)
8. _Git checkout -b "имя новой ветки" - создаст новую ветку и перейдет на нее
9. _Git diff_ - отличия текущего файла от сохраненного
10. Git diff "имя файла" - просмотр изменений, внесенных в файл
11. _Git checkout _ "название ветки" - переход на эту ветку

# Некоторые команды Markdown

> Цитирование
> Это пример цитирования возможностями Markdown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его (*), или знаком (_). Например, *Вот так*, или _Вот так_

Чтобы выделить текст полужирным необходимо обрамить его (**), или двойным знаком (__). Например, **Вот так**, или __вот так__

## Списки

Чтобы добавить ненумерованные списки необходимо пункты выделить (*) или знаком (+) Например, вот так:
* Элемент 1
* Элеиент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты пронумеровать, Например Вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет, здесь должен быть смайлик!](Улыбка.png), причем текст "Привет, здесь должен быть смайлик!" будет показан если не удастся загрузить изображение

# Работа с удаленными репозиториями

## команды из Git (локального репозитория)

* _git push origin main - отправляет изменения в удалённый репозиторий
* _git pull - Загрузка изменений с удаленного репозитория и объединение их с локальной копией
* _git clone адрес "удаленного репозитория" - клонирует репозиторий в текущую директорию

## Команды из Github

* _fork - скачиваем чужой публичный удаленный репозиторий 
* _pull requests - направляем свой вариант репозитория в чужой
