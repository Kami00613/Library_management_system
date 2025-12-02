Запрос 1 
Найти имена и электронные почты всех читателей, зарегистрированных после 1 января 2024 года.

`π name, email(σ registration_date>′ 2024 − 01 − 01 ′(Reader))`

Запрос 2 
Найти все книги (название, год издания) и их издателей (название издателя).

`π Book.title, Book.publication_year, Publisher.name(Book ⋈ Book.publisher_id = Publisher.publisher_id Publisher)`
