# Домашнее задание к занятию "Базы данных, их типы" - `Хамов Олег`

### Задание 1

1.1. Для этой цели подойдут такие СУБД как MySQL, PostgreSQL. Например, реляционные базы данных, или базы данных SQL обладают надежностью и неизменяемостью данных, что уменьшает риск потери информации. При обновлении данных их целостность гарантирована, они заменяются в одной таблице.

1.2. MySQL, потому что в итоге этот тип СУБД оказывается, во-первых, дешевле (хоть это и свободное ПО, затраты неизбежны), а во-вторых, более гибким и масштабируемым горизонтально, в отличие от того же PostgreSQL. MySQL одна из самых популярных и быстродействующих систем, таким образом, для задач подобного типа это наиболее рациональный выбор.

1.3. Для этих задач подойдет – MongoDB. Она рассчитана на работу с данными иерархической структуры, это документо-ориентированная система, т.е. в основе ее хранилище документов без использования таблиц. Таким образом, MongoDB обеспечивает простой доступ к данным, их хранение, ввод и извлечение, причем обработка данных простая и быстрая. Кроме того, несколько типов данных обрабатываются одновременно и для этой цели используется внутренний кэш. Поэтому это СУБД отлично подойдет для решения данных задач.

1.4. Можно использовать графовые СУБД, предназначенные для хранения информации, связанной с графами (узлы, вершины, связи между узлами). Хорошо подходят для социальных сетей, где требуется хранить связи между пользователями по разным критериям. Можно использовать такие СУБД как: ArangoDB, OrientDB, JanusGraph, Neo4j.

### Задание 2

2.1. 
1) Проверить есть ли нужная сумма на банковском счете; 
2) Ввести номер телефона; 
3) Подтвердить правильность телефона; 
4) ввести необходимую сумму;
5) Подтвердить оплату тем самым подтвердить перевод денежных средств со счета на баланс телефона; 
6) Проверить баланс телефона - необходимая сумма должна быть на счету телефона.

### Задание 3

3.1. Если сравнивать, то у SQL-баз данных есть ряд преимуществ по сравнению с NoSQL:
1. например, в SQL можно легко установить ограничения на доступ к данным для разных пользователей, а также, применять различные аутентификационные механизмы для обеспечения безопасности данных;
2. SQL-базы данных имеют жёстко определённый формат хранения данных, что делает их наиболее подходящим выбором для представления сложных связанных данных;
3. SQL-базы данных имеют лучшую поддержку транзакционности, что позволяет автоматически откатывать изменения при обнаружении проблемных транзакций и, таким образом, нивелировать возможные проблемы безопасности;
4. Гибкость запросов: SQL имеет очень мощный язык запросов, что делает его лучшим выбором для сложных запросов, связанных с большим количеством таблиц. С другой стороны, NoSQL имеет простой язык запросов, который хорошо подходит для запросов, связанных с большим количеством данных.
5. Скорость обработки: несмотря на то, что SQL обычно работает медленнее, чем NoSQL, его мощный язык запросов позволяет быстро обрабатывать сложные запросы. С другой стороны, NoSQL работает очень быстро с неструктурированными данными в больших объёмах.

### Задание 4

4.1. 

1. Задача - Нужно обрабатывать большое количество данных, но структура неизвестна и может быть различна для каждого документа
2. Критерии выбора:
- Много данных
- Не надо связывать
- Не знаем структуру
- Быстрый поиск
3. Тип БД - noSQL, документо-ориентированная
4. Пример СУБД - MongoDB

ИЛИ:

Можно использовать Hadoop — это программная платформа для сбора, хранения и обработки очень больших объемов данных. Проще говоря, это база данных, предназначенная для работы с большими данными. Набор утилит, библиотек и фреймворк для разработки и выполнения распределенных программ, работающих на кластерах из сотен и тысяч узлов.
Из преимуществ поисковые и контекстные механизмы высоконагруженных веб-сайтов и интернет-магазинов в том числе аналитики поисковых запросов и пользовательских логов, хранение, сортировка огромных объемов данных и разбор содержимого чрезвычайно больших файлов, быстрая обработка графических данных.














