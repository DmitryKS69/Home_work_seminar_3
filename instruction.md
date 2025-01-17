# Инструкция по языку MarkDown

Новая строка - это олна пустая строка

**Полужирный текст**

*Курсив текст*

## Цитирование
> Первый уровень
>> Второй уровень

## Списки
### Ненумерованные списки
* Лист 1
* Лист 2
### Нумерованные списки
1. Лист 1
2. Лист 2
3. Лист 3

## WEB ссылки
Текст [пример ссылки](http.example.com "Всплывающая подсказка")

## Работа с таблицами

Буква | Цифра | Символ
------ | ------|----------
a      | 4     | $
x      | 365    | (
b      |       | ^  

Буква|Цифра|Символ
---|---|---
a|4|$
 |365|(
b| |^  

Column | Column
------ | ------
\| Cell \|| \| Cell \|  


Column | Column | Column
:----- | :----: | -----:
Left   | Center | Right
align  | align  | align

## Картинки

### Это яблоко

![apple](apple.jpg)

### Это апельсин

![orange](orange.png)


## Основные команды при работе в GIT:
### _**git init**_ - запуск и создание репозитория (инициализация)
### *__git status__* - просмотр статуса (состояния) репозитория

### _**git add**_ - добавление файла для отслеживания

### *__git commit -m__* - фиксация (сохранение) состояния

### _**git diff**_ - показ разницы между сохранненными файлами
При этом красным цветом показываются удаленные строки, а зеленым - добавленные.

### __*git log*__ - вывод  всех сохраненных файлов

### __*git checkout*__ -  переход между коммитами

### __*git branch*__ - вывод всех веток. 

Дляя следующих команд немного изменим оформление.

Для клонирования репозитория себе на ПК используется команда:
> **git clone URL** - клонируется репозиторий по адресу **URL**

> **git pull** - составная команда для одновременного получения изменений и слияния с локальной версией

> **git push** - команда для отправки локальной версии репозитория на внешний.

Конец инструкции.