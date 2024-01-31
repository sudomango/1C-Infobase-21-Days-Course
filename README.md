## Описание проекта

В данном репозитории находится две информационные базы, созданные в ходе прохождения курса Евгения Гилёва "Программирование в 1С 8.3 – за 21 день" (далее просто "1С за 21 день"). Первая - создана в ходе выполнения заданий из видеоуроков, вторая - в ходе выполнения домашних заданий, которые выложены в курсе в качестве pdf-файлов.

Все домашние задания были выполнены самостоятельно, в чём можно убедиться, открыв журнал регистрации и посмотрев на все удачные и не очень эксперименты, сделанные в ходе выполнения :-)

**Евгений Гилёв - Курс "1С за 21 день", прохождение видеоуроков курса:**

Пройдены видеуроки и выполнены практические задания для дней 1 - 16. В том числе, была полностью пройдена часть обучения, посвящённая основным объектам бухгалтерского учёта и построению отчётов по ним ("Баланс" и "Закрытие месяца"). [Файл с архивом информационной базы](https://github.com/sudomango/1C-Infobase-21-Days-Course/blob/main/1C_Gilev_Base_Original.zip).

Скриншоты из Конфигуратора и из режима Предприятие:

![Application Screenshot 01](https://github.com/sudomango/1C-Infobase-21-Days-Course/blob/main/Application%20Screenshots/Application%20Screenshot%2001.jpg)

![Application Screenshot 02](https://github.com/sudomango/1C-Infobase-21-Days-Course/blob/main/Application%20Screenshots/Application%20Screenshot%2002.jpg)

![Application Screenshot 03](https://github.com/sudomango/1C-Infobase-21-Days-Course/blob/main/Application%20Screenshots/Application%20Screenshot%2003.jpg)

<hr>

**Евгений Гилёв - Курс "1С за 21 день", выполнение домашних заданий:**

Выполнены все домашние задания курса для дней 1 - 12. В ходе выполнения домашних заданий были рассмотрены и использованы практически все основные объекты конфигурации (справочники, документы, константы, перечисления, журналы документов, подсистемы, общие картинки, регистры накопления (два вида), регистры сведений, создано несколько отчётов, а также создана обработка, содержащая выполнение нескольких алгоритмических заданий). [Файл с архивом информационной базы](https://github.com/sudomango/1C-Infobase-21-Days-Course/blob/main/1C_Gilev_Base_Homework.zip).

**Помимо этого, в документе "Поступление Товаров" реализованы:**

* Проверка типа контрагента (что это именно поставщик).

* Автоматическое заполнение реквизита "Ответственный Менеджер" на основе информации о поставщике.

* Автоматический расчёт суммы для каждого товара (если введены количество и цена единицы товара).

* Автоматический расчёт цены закупки для каждого товара (если введены только количество и общая сумма).

* Автоматический подсчёт итоговой суммы документа перед записью документа.

* Проведение документа по нескольким регистрам с дальнейшей ручной оптимизацией кода.

<br>

**В документе "Реализация Товара" реализованы:**

* Проверка типа контрагента (что это именно клиент).

* Автоматическое заполнение реквизита "Ответственный Менеджер" на основе информации о клиенте.

* Автоматический расчёт суммы продажи для каждого товара.

* Автоматическое получение цены для каждой номенклатурной позиции из регистра сведений.

* Если сумма продажи товара вводится руками (форсированно), то цена за единицу адаптируется к новой сумме.

* Контроль остатков товара при попытке реализации с помощью запроса к базе данных.

* Автоматический подсчёт итоговой суммы документа перед записью документа.

* Реализация механизма ввода на основании (на основе документа "Поступление Товаров").

* Создан и отредактирован макет печатной формы, в том числе код процедуры Печать в модуле менеджера документа.

* Проведение документа по нескольким регистрам с дальнейшей ручной оптимизацией кода.

Скорее всего, это не полный список освоенных механизмов и технологий (как минимум, за рамками осталась работа с отчётами, языком запросов и СКД), но так как курс Евгения Гилёва достаточно известен в среде разработчиков 1С, надеюсь, что описывать все его задания полностью нет никакой необходимости 😊.

Скриншоты из Конфигуратора и из режима Предприятие:

![Application Screenshot 04](https://github.com/sudomango/1C-Infobase-21-Days-Course/blob/main/Application%20Screenshots/Application%20Screenshot%2004.png)

![Application Screenshot 05](https://github.com/sudomango/1C-Infobase-21-Days-Course/blob/main/Application%20Screenshots/Application%20Screenshot%2005.png)
