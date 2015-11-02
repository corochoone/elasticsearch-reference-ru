# elasticsearch-reference-ru
Russian translation of the Elastic Search Reference (Русский перевод [Elasticsearch Reference](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html))

Для работы необходимо:

 1. Скачать полную версию руководства из репы [Elasticsearch](https://github.com/elastic/elasticsearch) и распаковать
 2. Отклонировать каталог docs в docs.ru, перенести туда файлы из данного репозитория какие найдутся
 3. Скачать набор инструментов для генерации документации из репы [Elastic/docs](https://github.com/elastic/docs)
 4. Сделать симлинк (или скопировать) туда склонированный каталог docs.ru
 5. Создать в корневом каталоге набора инструментов подкаталог html/ru/elasticsearch/reference/**нужная_версия**
 6. Выполнить команду из корневого каталога набора инструментов:

`./build_docs.pl --chunk=1 --doc ./docs.ru/reference/index.asciidoc --out ./html/ru/elasticsearch/reference/нужная_версия/`

Далее в html/ru/elasticsearch/reference/**нужная_версия** должны появится файлы с русским текстом и вы можете читать их через браузер локально или выложить куда-либо на хостинг, но помните о том, что написано здесь: [Условия использования](https://github.com/elastic/docs/blob/master/README.asciidoc).

Мыло для связи: corochoone[at]gmail[dot]dom
