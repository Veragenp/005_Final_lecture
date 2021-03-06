**План тестирования возможности записи на обучение профессии "Тестировщик ПО" на сайте https://netology.ru/**

**Цель:** тестирование возможности записи на обучение профессии "Тестировщик ПО".

**Этапы тестирования**

1. Выполнить подготовку тестовых данных: логин и пароль для зарегистрированного пользователя;
2. Разработать тесты в соответствии с этапами тестирования:

_Условие: пользователь не зарегистрирован_
* Выполнить проверку перехода на страницу профессии "Тестировщик ПО" (см. сценарии 1.1...1.7);
* Выполнить переход на форму записи (см. сценарии 4.1...4.3);
* Выполнить проверку полей (см. сценарии 5.1...5.3);
* Выполнить проверку формы отправки (см. сценарии 6.1...6.9, 7.1).

_Условие: пользователь зарегистрирован_
* Войти на сайт как зарегистрированный пользователь (см. сценарий 2.1);
* Выполнить проверку перехода на страницу профессии "Тестировщик ПО" (см. сценарии 3.1...3.7);
* Выполнить переход на форму записи (см. сценарии 4.1...4.3);
* Выполнить проверку полей (см. сценарии 5.1, 5.2);
* Выполнить проверку формы отправки (см. сценарии 8.1...8.9, 9.1).

В качестве валидных данных для отправки формы использовать:
- Имя - Вася;
- Телефон - 892344070806;
 - Электронная почта - testUser@gmail.com

В качестве не валидных данных для отправки формы использовать:
- Имя - 78Дима;
- Телефон - 8923440789430806; 
- Электронная почта - testUser@gmailcom

3 Выполнить оценку результатов тестирования на основании отчетов, подготовленных с использованием фреймворка Allure.

**Перечень автоматизируемых сценариев**

_Переход на страницу профессии "Тестировщик ПО". Сценарий 1.1 (не зарегистрированный пользователь)_
1. Открыть сайт https://netology.ru/;
2. Кликнуть по кнопке в левом верхнем углу главной страницы "Каталог курсов";
3. В перечне направлений обучения выбрать раздел "Программирование", навести на данный раздел курсор;
4. Во всплывающем списке "Для начинающих" выбрать курс "Тестировщик ПО", кликнуть на него.


_Переход на страницу профессии "Тестировщик ПО". Сценарий 1.2 (не зарегистрированный пользователь)_
1. Открыть сайт https://netology.ru/;
2. Кликнуть по кнопке в левом верхнем углу главной страницы "Каталог курсов";
3. В перечне направлений обучения выбрать раздел "Программирование", кликнуть на раздел;
4. На странице со списком курсов выбрать курс "Тестировщик ПО", кликнуть на него.


_Переход на страницу профессии "Тестировщик ПО". Сценарий 1.3 (не зарегистрированный пользователь)_
1. Открыть сайт https://netology.ru/;
2. В разделе "Направления обучения" выбрать направление "Программирование", кликнуть по нему;
3. В списке курсов выбрать курс "Тестировщик ПО", кликнуть на него;


_Переход на страницу профессии "Тестировщик ПО". Сценарий 1.4 (не зарегистрированный пользователь)_
1. Открыть сайт https://netology.ru/;
2. В разделе "Направления обучения" выбрать направление "Программирование", кликнуть по нему;
3. В окне поиска внести поисковое слово "Тестировщик", в появившемся списке выбрать курс "Тестировщик ПО", кликнуть по нему.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 1.5 (не зарегистрированный пользователь)_
1. Открыть сайт https://netology.ru/;
2. Прокрутить страницу до нижней части страницы;
3. В разделе "обучение" выбрать раздел "Каталог курсов", кликнуть по нему;
4. В окне поиска внести поисковое слово "Тестировщик", в появившемся списке выбрать курс "Тестировщик ПО", кликнуть по нему.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 1.6 (не зарегистрированный пользователь)_
1. Открыть сайт https://netology.ru/;
2. Прокрутить страницу до нижней части страницы;
3. В разделе "обучение" выбрать раздел "Популярные курсы", кликнуть по нему;
4. В списке выбрать курс "Тестировщик ПО", кликнуть по нему.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 1.7 (не зарегистрированный пользователь)_
1. Открыть сайт https://netology.ru/;
2. Прокрутить страницу до нижней части страницы;
3. В разделе "обучение" выбрать раздел "Программирование", кликнуть по нему;
4. В списке выбрать курс "Тестировщик ПО", кликнуть по нему.

_Вход на сайт как зарегистрированный пользователь. Сценарий 2.1_
1. Открыть сайт https://netology.ru/;
2. Кликнуть по кнопке в правом верхнем углу главной страницы "Войти";
3. В поле Emeil ввести валидную электронную почту;
4. В поле "Пароль" ввести валидный пароль;
5. Кликнуть на кнопку "Войти";
6. Выполнен переход на страницу личного кабинета.


_Переход на страницу профессии "Тестировщик ПО". Сценарий 3.1 (зарегистрированный пользователь)_
1. Выполнить сценарий 2.1;
2. Кликнуть по кнопке в левом верхнем углу главной страницы "Каталог курсов";
3. В перечне направлений обучения выбрать раздел "Программирование", навести на данный раздел курсор;
4. Во всплывающем списке "Для начинающих" выбрать курс "Тестировщик ПО", кликнуть на него.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 3.2 (зарегистрированный пользователь)_
1. Выполнить сценарий 2.1;
2. Кликнуть по кнопке в левом верхнем углу главной страницы "Каталог курсов";
3. В перечне направлений обучения выбрать раздел "Программирование", кликнуть на раздел;
4. На странице со списком курсов выбрать курс "Тестировщик ПО", кликнуть на него.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 3.3 (зарегистрированный пользователь)_
1. Выполнить сценарий 2.1;
2. Перейти на главную страницу - кликнуть по значку "Нетология" в правом верхнем углу сайта;
3. В разделе "Направления обучения" выбрать направление "Программирование", кликнуть по нему;
4. В списке курсов выбрать курс "Тестировщик ПО", кликнуть на него.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 3.4 (зарегистрированный пользователь)_
1. Выполнить сценарий 2.1;
2. Перейти на главную страницу - кликнуть по значку "Нетология" в правом верхнем углу сайта;
3. В разделе "Направления обучения" выбрать направление "Программирование", кликнуть по нему;
4. В окне поиска внести поисковое слово "Тестировщик", в появившемся списке выбрать курс "Тестировщик ПО", кликнуть по нему.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 3.5 (зарегистрированный пользователь)_
1. Выполнить сценарий 2.1;
2. Прокрутить страницу до нижней части страницы;
3. В разделе "обучение" выбрать раздел "Каталог курсов", кликнуть по нему;
4. В окне поиска внести поисковое слово "Тестировщик", в появившемся списке выбрать курс "Тестировщик ПО", кликнуть по нему.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 3.6 (зарегистрированный пользователь)_
1. Выполнить сценарий 2.1;
2. Прокрутить страницу до нижней части страницы;
3. В разделе "обучение" выбрать раздел "Популярные курсы", кликнуть по нему;
4. В списке выбрать курс "Тестировщик ПО", кликнуть по нему.

_Переход на страницу профессии "Тестировщик ПО". Сценарий 3.7 (зарегистрированный пользователь)_
1. Выполнить сценарий 2.1;
2. Прокрутить страницу до нижней части страницы;
3. В разделе "обучение" выбрать раздел "Программирование", кликнуть по нему;
4. В списке выбрать курс "Тестировщик ПО", кликнуть по нему.


_Переход на форму записи. Сценарий 4.1 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на страницу профессии "Тестировщик ПО";
2. Прокрутить колесико мыши до формы с заголовком "Запишитесь или получите консультацию".

_Переход на форму записи. Сценарий 4.2 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на страницу профессии "Тестировщик ПО";
2. Кликнуть на кнопку "Записаться" на странице профессии.

_Переход на форму записи. Сценарий 4.3 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на страницу профессии "Тестировщик ПО";
2. Прокрутить колесико мыши до фразы "Тестировщик следит за качеством программного продукта". 
3. В верхней части страницы появится всплывающее окно с кнопкой "Записаться", кликнуть на кнопку.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.1 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Рарарарарарарар" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.2 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Рарарарарарара" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.3 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Ян" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.4 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "том" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.5 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Анна-Мария" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.6 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Tom" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.7 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение ""Вася"" (в одних ковычках);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.8 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Анна Мария" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.9 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Иван" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.10 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Семён" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена зеленой рамкой, строка имя заполнено.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.11 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Рарарарарарарафф" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена красной рамкой, под рамкой предупреждение красными буквами: "Недопустимое имя пользователя".

_Проверка полей формы. Поле "Имя" Сценарий 5.1.12 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "д" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена красной рамкой, под рамкой предупреждение красными буквами: "Должно быть не короче 2 символов".

_Проверка полей формы. Поле "Имя" Сценарий 5.1.13 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Вася>" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена красной рамкой, под рамкой предупреждение красными буквами: "Должно состоять из букв".

_Проверка полей формы. Поле "Имя" Сценарий 5.1.14 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "12" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена красной рамкой, под рамкой предупреждение красными буквами: "Должно состоять из букв".

_Проверка полей формы. Поле "Имя" Сценарий 5.1.15 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "Вася12" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Ожидаемый результат - строка "Имя" подсвечена красной рамкой, под рамкой предупреждение красными буквами: "Должно состоять из букв".

_Проверка полей формы. Поле "Имя" Сценарий 5.1.16 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "<script>alert("I hacked this!")</script>" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Нажать на кнопку "Записаться";
5. Ожидаемый результат - строка "Имя" подсвечена красной рамкой, под рамкой предупреждение красными буквами: "Должно состоять из букв". Отправка формы не выполнена.

_Проверка полей формы. Поле "Имя" Сценарий 5.1.17 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле значение "FOO'); DROP TABLE USERS" (без ковычек);
3. Заполнить поля "Электронная почта", "Номер телефона" валидными значениями;
4. Нажать на кнопку "Записаться";
5. Ожидаемый результат - строка "Имя" подсвечена красной рамкой, под рамкой предупреждение красными буквами: "Должно состоять из букв". Отправка формы не выполнена.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.1 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "+71234567891425";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.2 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "71234567891425";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.3 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "123456789";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.4 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "+712345678914251";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.5 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "+712345678914251";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.6 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "7-123-45-678-91-425";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.7 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "7-123-45--678-91-425";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.8 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "+7(923)-427-43-02";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.9 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "8 923 403 43 54";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.10 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "++79234050203";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.11 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "+7923405+0203+";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.12 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "12345678";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена красной рамкой, под рамкой предупреждение "Номер в формате +9(999)9999-99-99.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.13 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "726345дл2323";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена красной рамкой, под рамкой предупреждение "Номер в формате +9(999)9999-99-99.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.14 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" "7923*4050203";
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена красной рамкой, под рамкой предупреждение "Номер в формате +9(999)9999-99-99.

_Проверка полей формы. Поле "Телефон" Сценарий 5.2.15 (не зарегистрированный/зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Телефон" три пробела;
3. Заполнить поля "Имя", "Электронная почта" валидными значениями;
4. Ожидаемый результат - строка "Телефон" подсвечена красной рамкой, под рамкой предупреждение "Поле обязательно для заполнения".


_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.1 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "вася@москва.рф";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.2 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "{v/e.r+a*o_p-t}@mail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.3 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "vasya@mail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.4 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "{v/e.r+a*#o_p_8}@mail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.5 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "Vasya@mail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.6 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "VASYA@mail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.7 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "VASYA@m-a.i.8_5-l.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.8 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd@nvh.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.9 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "dddddd@dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddcnvhаааа.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.10 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение "dddddd@ааа.rudsdsdsdsdsdsdsdsdddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddv";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена зеленой рамкой, в поле внесены данные.

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.11 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "Vasya@mailru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.12 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "Vasyamailюru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.13 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "ddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddV@nvh.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.14 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "dddddd@ddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddcnvhаааа.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.15 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "dddddd@ааа.rudsdsdsdsdsdsdsdsdddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddv";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.16 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "vlad@hаааа.r";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.17 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "vasya win@mail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.18 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "vasya@m ail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка полей формы. Поле "Электронная почта" Сценарий 5.3.19 (не зарегистрированный пользователь)_
1. Перейти на форму записи;
2. Внести в поле "Электронная почта" значение  "@mail.ru";
3. Заполнить поля "Имя", "Телефон" валидными значениями;
4. Ожидаемый результат - строка "Электронная почта" подсвечена красной рамкой, предупреждение "Неверный emeil".

_Проверка отправки формы (запись). Сценарий 6.1. Позитивный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" валидным значением;
2. Заполнить поле "Телефон" валидным значением;
3. Заполнить поле "Электронная почта" валидным значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - переход на страницу оплаты, текст с уведомлением "Вы записались на курс" ("Скоро вам позвонят").

_Проверка отправки формы (запись). Сценарий 6.2. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" валидным значением;
2. Заполнить поле "Телефон" не валидным значением;
3. Заполнить поле "Электронная почта" не валидным значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, под полем "Телефон" предупреждение красным "Номер в формате +9(999)999-99-99", под полем "Электронная почта" предупреждение "Неверный Emeil".

_Проверка отправки формы (запись). Сценарий 6.3. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" валидным значением;
2. Заполнить поле "Телефон" пустым значением;
3. Заполнить поле "Электронная почта" пустым значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, под полями "Телефон", "Электронная почта", предупреждение "Обязательное поле".

_Проверка отправки формы (запись). Сценарий 6.4. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" не валидным значением;
2. Заполнить поле "Телефон" валидным значением;
3. Заполнить поле "Электронная почта" пустым значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, под полем "Электронная почта", предупреждение "Обязательное поле",
   под полем "Имя" предупреждение "Должно состоять из букв".

_Проверка отправки формы (запись). Сценарий 6.5. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" не валидным значением;
2. Заполнить поле "Телефон" не валидным значением;
3. Заполнить поле "Электронная почта" пустым значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, "Электронная почта", предупреждение
   "Обязательное поле", под полем "Имя" предупреждение "Должно состоять из букв", под полем "Телефон" - "Номер в формате +9(999)999-99-99"

_Проверка отправки формы (запись). Сценарий 6.6. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" не валидным значением;
2. Заполнить поле "Телефон" пустым значением;
3. Заполнить поле "Электронная почта" не валидным значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, "Электронная почта", предупреждение
   "Неверный emeil", под полем "Имя" предупреждение "Должно состоять из букв", под полем "Телефон" - "Обязательное поле"

_Проверка отправки формы (запись). Сценарий 6.7. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" пустым значением;
2. Заполнить поле "Телефон" валидным значением;
3. Заполнить поле "Электронная почта" не валидным значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, "Электронная почта", предупреждение
   "Неверный emeil", под полем "Имя" предупреждение "Обязательное поле"

_Проверка отправки формы (запись). Сценарий 6.8. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" пустым значением;
2. Заполнить поле "Телефон" не валидным значением;
3. Заполнить поле "Электронная почта" пустым значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, "Электронная почта", предупреждение
   "Обязательное поле", под полем "Имя" предупреждение "Обязательное поле", под полем "Телефон" - "Номер в формате +9(999)999-99-99"

_Проверка отправки формы (запись). Сценарий 6.9. Негативный. Не зарегистрированный пользователь_
1. Заполнить поле "Имя" пустым значением;
2. Заполнить поле "Телефон" пустым значением;
3. Заполнить поле "Электронная почта" валидным значением;
4. Нажать на кнопку "Записаться" ("Получить консультацию").
5. Ожидаемый результат - отправка формы не выполнена, под полем "Имя" предупреждение "Обязательное поле", под полем "Телефон" - "Обязательное поле"

_Проверка отправки формы (получить консультацию). Сценарий 7.1. Не зарегистрированный пользователь_
1. Повторить сценарии 6.1...6.9.


_Проверка отправки формы (запись). Сценарий 8.1. Позитивный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" валидным значением;
2. Заполнить поле "Телефон" валидным значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - переход на страницу оплаты, текст с уведомлением "Вы записались на курс" ("Скоро вам позвонят").

_Проверка отправки формы (запись). Сценарий 8.2. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" валидным значением;
2. Заполнить поле "Телефон" не валидным значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Телефон" - "Номер в формате +9(999)999-99-99"

_Проверка отправки формы (запись). Сценарий 8.3. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" валидным значением;
2. Заполнить поле "Телефон" пустым значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Телефон" - "Обязательное поле"

_Проверка отправки формы (запись). Сценарий 8.4. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" не валидным значением;
2. Заполнить поле "Телефон" валидным значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Имя" предупреждение "Должно состоять из букв"

_Проверка отправки формы (запись). Сценарий 8.5. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" не валидным значением;
2. Заполнить поле "Телефон" пустым значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Имя" предупреждение "Должно состоять из букв", под полем телефон "Обязательное поле"

_Проверка отправки формы (запись). Сценарий 8.6. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" не валидным значением;
2. Заполнить поле "Телефон" не валидным значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Имя" предупреждение "Должно состоять из букв", под полем телефон "Номер в формате +9(999)999-99-99"

_Проверка отправки формы (запись). Сценарий 8.7. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" пустым значением;
2. Заполнить поле "Телефон" валидным значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Имя" предупреждение "Обязательное поле"

_Проверка отправки формы (запись). Сценарий 8.8. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" пустым значением;
2. Заполнить поле "Телефон" не валидным значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Имя" предупреждение "Обязательное поле", под полем телефон "Номер в формате +9(999)999-99-99"

_Проверка отправки формы (запись). Сценарий 8.9. Негативный. Зарегистрированный пользователь_
1. Заполнить поле "Имя" пустым значением;
2. Заполнить поле "Телефон" пустым значением;
3. Нажать на кнопку "Записаться" ("Получить консультацию").
4. Ожидаемый результат - отправка формы не выполнена, под полем "Имя" предупреждение "Обязательное поле", под полем телефон "Обязательное поле"

_Проверка отправки формы (получить консультацию). Сценарий 9.1. Зарегистрированный пользователь_
1. Повторить сценарии 8.1...8.9.

   
**Перечень используемых инструментов с обоснованием выбора**
1. Selenide - среда для автоматизированного тестирования веб-приложений. В данной задаче требуется протестировать
   web-сайт, тестируем с использованием инструментов Selenide;
2. Java 11 - используется для разработки автотестов;
3. Junit5 - выполняем тестирование web-сайта при помощи языка Java, данная среда предназначена для тестирования приложений Java;
4. Java-Faker - библиотека применена для создания тестовых данных: имя, телефон, электронная почта.
5. Gradle - так как в данном проекте используются различные библиотеки и фреймворки, требуется инструмент для сборки проекта. Данный инструмент применен для сборки проекта.
6. Allure - нужно проанализировать результаты тестирования, для этого используем фреймворк для создания отчетов.
7. IntelliJ IDEA - инструмент для работы с проектом;
8. Docker - для работы с базой данных сайта (например для записи контактных данных пользователя).


**Перечень необходимых разрешений/данных/доступов**
1. Технические требования к заполнению полей: "Имя", "Номер телефона", "Электронная почта";
2. Техническая документация к модулю "Отправка формы";  
3. Разрешение от руководства для проведения тестирования;
4. Тестовые данные: зарегистрированный пользователь (валидный логин, валидный пароль);
5. Доступ к базе данных и API.

**Перечень и описание возможных рисков при автоматизации**
1. Автотесты проверяют только то на что запрограммирован, в случае не учета какого-либо сценария, подобный сценарий покрыт не будет; 
2. В случае изменения наполнения страницы, добавления каких-либо дополнительных полей потребуется корректировка тестов, постоянная поддержка тестов;
3. Не верная оценка трудозатрат на автотестировании;
4. Трудности при поиске локаторов элементов на страницах. Риски, связанные с изменением структуры сайта и последующей корректировкой локаторов.


**Перечень необходимых специалистов для автоматизации**

* QA-middle (Автотестирование)
* QA-junior (Автотестирование, ручное тестирование)

**Интервальная оценка с учетом рисков (в часах)**
* QA-middle - постановка задачи, проверка решений, обработка результатов - 6 ч.
* QA-junior - разработка проекта по автоматизации тестирования - 24 ч.
* QA-junior - проверка юзабилити, грамматических ошибок, дизайна - 2 ч.








