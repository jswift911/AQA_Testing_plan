# План автоматизации тестирования возможности записаться на курс "Тестировщик ПО"

## Автоматизируемые сценарии

1. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов и заполнением формы внизу страницы с валидными данными:
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: успешная отправка формы.

2. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов и заполнением формы внизу страницы с невалидными данными в поле "Имя":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение инпута "Имя" невалидными данными (слишком длинное поле, цифры или спецсимволы);
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Должно состоять из букв".
   
3. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов и заполнением формы внизу страницы с невалидными данными в поле "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" невалидными данными (буквы на латинице/кирилице, спецсимволы);
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Номер в формате +9 (999) 999-99-99".
   
4. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов и заполнением формы внизу страницы с пустыми полем "Имя":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Не заполнение поля "Имя";
   - Заполнение поля "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Обязательное поле".

5. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов и заполнением формы внизу страницы с пустым полем "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение поля "Имя" валидными данными;
   - Не заполнение поля "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Обязательное поле".

6. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов и заполнением формы внизу страницы с пустыми полями "Имя" и "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Не заполнение обоих полей "Имя" и "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибок валидации под полями "Имя" и "Телефон" с текстом "Обязательное поле".

5. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в хедере с валидными данными:
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: успешная отправка формы.
   
6. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в хедере с невалидными данными в поле "Имя":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение инпута "Имя" невалидными данными (слишком длинное поле, цифры или спецсимволы);
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Должно состоять из букв".
   
7. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в хедере с невалидными данными в поле "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" невалидными данными (буквы на латинице/кирилице, спецсимволы);
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Номер в формате +9 (999) 999-99-99".
   
8. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в хедере с пустым полем "Имя":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по кнопке "Записаться" в хедере;
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Не заполнение поля "Имя";
   - Заполнение поля "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Обязательное поле".

8. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в хедере с пустым полем "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по кнопке "Записаться" в хедере;
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение поля "Имя" валидными данными;
   - Не заполнение поля "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Обязательное поле".

8. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в хедере с пустыми полями "Имя" и "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по кнопке "Записаться" в хедере;
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Не заполнение обоих полей "Имя" и "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибок валидации под полями "Имя" и "Телефон" с текстом "Обязательное поле".

9. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в разделе "Обучение для разных целей" с валидными данными:
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: успешная отправка формы.
   
10. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в разделе "Обучение для разных целей" с невалидными данными в поле "Имя":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение инпута "Имя" невалидными данными (слишком длинное поле, цифры или спецсимволы);
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Должно состоять из букв".
   
11. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в разделе "Обучение для разных целей" с невалидными данными в поле "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" невалидными данными (буквы на латинице/кирилице, спецсимволы);
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Номер в формате +9 (999) 999-99-99".
   
12. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в разделе "Обучение для разных целей" с пустым полем "Имя":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Не заполнение поля "Имя";
   - Заполнение поля "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Обязательное поле".

12. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в разделе "Обучение для разных целей" с пустым полем "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение поля "Имя" валидными данными;
   - Не заполнение поля "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Обязательное поле".

12. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов через кнопку "Записаться" в разделе "Обучение для разных целей" с пустыми полями "Имя" и "Телефон":
   - Клик по кнопке "Каталог курсов" на главной странице;
   - Клик по разделу "Программирование" из выпадающего окна;
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Не заполнение обоих полей "Имя" и "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибок валидации под полями "Имя" и "Телефон" с текстом "Обязательное поле".

13. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта и заполнением формы внизу страницы с валидными данными:
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: успешная отправка формы.
   
14. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта и заполнением формы внизу страницы с невалидными данными в поле "Имя":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение инпута "Имя" невалидными данными (слишком длинное поле, цифры или спецсимволы);
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Должно состоять из букв".
   
15. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта и заполнением формы внизу страницы с невалидными данными в поле "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" невалидными данными (буквы на латинице/кирилице, спецсимволы);
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Номер в формате +9 (999) 999-99-99".
   
16. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта и заполнением формы внизу страницы с пустым полем "Имя":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Не заполнение поля "Имя";
   - Заполнение поля "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Обязательное поле".

16. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта и заполнением формы внизу страницы с пустым полем "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Заполнение поля "Имя" валидными данными;
   - Не заполнение поля "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Обязательное поле".

16. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта и заполнением формы внизу страницы с пустыми полями "Имя" и "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка страницы вниз до формы записи;
   - Не заполнение обоих полей "Имя" и "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибок валидации под полями "Имя" и "Телефон" с текстом "Обязательное поле".

17. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в хедере с валидными данными:
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: успешная отправка формы.
   
18. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в хедере с невалидными данными в поле "Имя":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение инпута "Имя" невалидными данными (слишком длинное поле, цифры или спецсимволы);
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Должно состоять из букв".
   
19. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в хедере с невалидными данными в поле "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" невалидными данными (буквы на латинице/кирилице, спецсимволы);
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Номер в формате +9 (999) 999-99-99".
   
20. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в хедере с пустым полем "Имя":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Не заполнение поля "Имя";
   - Заполнение поля "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Обязательное поле".

20. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в хедере с пустым полям "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Заполнение поля "Имя" валидными данными;
   - Не заполнение поля "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Обязательное поле".

20. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в хедере с пустыми полями "Имя" и "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Клик по кнопке "Записаться" в хедере;
   - Не заполнение обоих полей "Имя" и "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибок валидации под полями "Имя" и "Телефон" с текстом "Обязательное поле".

21. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в разделе "Обучение для разных целей" с валидными данными:
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: успешная отправка формы.
   
22. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта ччерез кнопку "Записаться" в разделе "Обучение для разных целей" с невалидными данными в поле "Имя":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение инпута "Имя" невалидными данными (слишком длинное поле, цифры или спецсимволы);
   - Заполнение инпута "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Должно состоять из букв".
   
23. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в разделе "Обучение для разных целей" с невалидными данными в поле "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение инпута "Имя" валидными данными;
   - Заполнение инпута "Телефон" невалидными данными (буквы на латинице/кирилице, спецсимволы);
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Номер в формате +9 (999) 999-99-99".

24. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в разделе "Обучение для разных целей" с пустым полем "Имя":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Не заполнение поля "Имя";
   - Заполнение поля "Телефон" валидными данными;
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Имя" с текстом "Обязательное поле".

24. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в разделе "Обучение для разных целей" с пустым полем "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Заполнение поля "Имя" валидными данными;
   - Не заполнение поля "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибки валидации под полем "Телефон" с текстом "Обязательное поле".

24. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта через кнопку "Записаться" в разделе "Обучение для разных целей" с пустыми полями "Имя" и "Телефон":
   - Прокрутка до раздела "Направления обучения" на главной странице;
   - Клик по разделу "Программирование";
   - Прокрутка до профессии "Тестировщик ПО";
   - Клик по профессии "Тестировщик ПО";
   - Прокрутка до раздела "Обучение для разных целей"
   - Клик по кнопке "Записаться" раздела "Обучение для разных целей";
   - Не заполнение обоих полей "Имя" и "Телефон";
   - Клик по кнопке "Записаться".

   Ожидаемый результат: появление ошибок валидации под полями "Имя" и "Телефон" с текстом "Обязательное поле".

## Используемые инструменты

1. [Selenium](https://www.selenium.dev/) – платформа для автоматизированного тестирования веб-приложений, которая позволяет создавать скрипты на языке программирования и выполнять их в браузере.
2. [Java](https://www.java.com/) – язык программирования, который часто используется для написания автоматизированных тестов на Selenium WebDriver. Он имеет широкие возможности и хорошую документацию.
3. [Git](https://git-scm.com/) – система контроля версий, которая позволяет хранить и управлять исходным кодом тестов.
4. [Gradle](https://gradle.org/) - система автоматической сборки под язык Java.
5. [JUnit 5](https://junit.org/junit5/) – фреймворк для написания и запуска тестов на Java.
6. [Allure Framework](https://github.com/allure-framework/allure-java) – отчетный фреймворк для Java, который позволяет отображать результаты тестирования в читабельном виде.

## Необходимые разрешения, данных и доступы

1. Разрешение на выполнение автоматизации тестирования у владельца сайта.
2. Доступ к исходному коду сайта для анализа элементов и составления локаторов на них.
3. Доступ к базе данных и API сайта для проверки ожидаемых результатов.

## Возможные риски при автоматизации

1. Изменение макета сайта может вызвать проблемы с локаторами элементов, что потребует дополнительной работы по обновлению тестовых скриптов.
2. Нарушение разрешений и доступов может привести к неработоспособности автоматизированных тестов.
3. Использование сложных локаторов, особенно в случаях, когда макет сайта изменяется динамически, также может вызывать проблемы с работой тестовых скриптов.

## Необходимые специалисты для автоматизации

1. Инженер-тестировщик по автоматизации, который обладает опытом работы с инструментами Selenium, Java, Git, JUnit 5, и Allure Framework, а также знаниями по ручному тестированию.

## Интервальная оценка с учётом рисков в часах

1. Переход к странице профессии «Тестировщик ПО» со страницы каталога курсов – 4 часа.
2. Переход к странице профессии «Тестировщик ПО» через некоторый контент на главной странице сайта – 6 часов.
3. Переход к форме записи со страницы профессии «Тестировщик ПО» по нажатию кнопки «Записаться» – 4 часа.
4. Заполнение формы записи на обучение профессии «Тестировщик ПО»:
   - Позитивный сценарий – 6 часов.
   - Негативные сценарии – 12 часов.
5. Настройка окружения и установка необходимых инструментов – 8 часов.
6. Написание и отладка автоматизированных тестов – 40 часов.
7. Создание отчетов о пройденных тестах в Allure Framework – 10 часов.

**Итого: 90 часов.**

С учетом возможных рисков, связанных с изменением макета сайта и нарушением разрешений и доступов, необходимо добавить еще 15 часов на работу по обновлению тестовых скриптов.

Итоговая интервальная оценка с учетом рисков составляет **90-105 часов.**
