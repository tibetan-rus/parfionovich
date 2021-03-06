# Что

Переверстка книги Парфионович Ю.М. "Тибетский письменный язык" в TeX

# Почему

Книга содержит уникальный материал, необходимый для глубокого понимания тибетского письменного языка
Оригинальное издание от 1970 и его переиздания содержат написанный от руки плохочитаемый тибетский текст, книгу тяжело использовать как справочник по языку.

# Цель

* Сохранить оригинальный текст, дать книге современную электронную форму.
* Добавить дополнительные примечания для читателей-нелингвистов для облегчения понимания текста

# Технические параметры

* Для сборки в PDF достаточно установить пакет teX-Live
* Текст набирается в коидровке UTF-8
* Для текста на тибетском используется шрифт Tibetan Machine Uni
* Для текстов вида <тибетский оригинал>, <тибетский оригинал><транслитерация> и <тибетский оригинал><транслитерация><перевод на русский> добавлены макросы \prfA{#1} \prfB{#1}{#2} \prfC{#1}{#2}{#3}
* Для сносок оригинального текста используется команда стиля \footnote[N]{текст}, для дополнительных примечаний добавлена команда \prfnote{текст}

# Если у тебя есть желание помочь...

или увидел опечатку, ошибку в тексте, или более искусный TeXник, то можно
* сделать pull request
* открыть issue
* или написать на khirn01@gmail.com