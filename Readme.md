AJS_Regex_Phone-number


---
## Домашнее задание к лекции «Регулярные выражения»

**Важно**: каждая задача выполняется в виде отдельного проекта с собственным GitHub репозиторием.

**Важно**: код должен проходить ESLint без ошибок.

**Важно**: тесты должны обеспечивать 100% покрытие тестируемых функций по строкам.

**Важно**: решения должны быть построены на базе [шаблона Webpack](/ci-template).

В личном кабинете на сайте [netology.ru](http://netology.ru/) в поле комментария к домашней работе вставьте ссылки на ваш GitHub-проекты.

---
## Телефоны (задача со звёздочкой)

**Важно**: данная задача не является обязательной 

### Легенда

Вам поручили подумать над тем, чтобы реализовать очистку вводимых номеров телефонов в любом формате (например, как на Госуслугах) и приведения к единому формату: +7xxxxxxxxxx (где вместо x - цифры).

Вам нужно подумать - какой инструмент использовать и выбрать оптимальное, на ваш взгляд, решение (не факт, что оно уместиться в одну строку).

### Описание

Что мы хотим видеть, мы хотим, что ваша функция работала следующим образом:
* 8 (927) 000-00-00 -> +79270000000
* +7 960 000 00 00 -> +79600000000
* +86 000 000 0000 -> +860000000000

В последнем номере нет ошибки, это Китай. А первые два - РФ.

Не забудьте написать unit-тесты, которые обеспечивают 100% покрытие функций и классов, которые вы тестируете.

---