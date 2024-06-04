# 1. Перечень автоматизируемых сценариев.
## Переход с главной страницы сайта на страницу с профессией "Тестировщик ПО:
_Предусловие_: Находимся на главной странице сайта [Нетологии](https://netology.ru/).

### №1
1. В хедере кликнуть "Каталог курсов".
2. В появившуюся поисковую строку начать вводить название профессии.
3. Из предложенных кликнуть по нужной профессии.

### №2
1. В хедере кликнуть "Каталог курсов".
2. В появившуюся поисковую строку ввести название профессии.
3. Кликнуть "Найти курс".
4. Кликнуть по нужной профессии из найденных.

### №3
1. В хедере кликнуть "Каталог курсов".
2. В появившемся разделе "Направления обучения" кликнуть "Все курсы".
3. Выбрать и кликнуть нужную профессию из предложенного списка.

### №4
1. В хедере кликнуть "Каталог курсов".
2. В появившемся разделе "Направления обучения" кликнуть "Программирование".
3. Выбрать и кликнуть нужную профессию из предложенного списка.

### №5
1. В блоке "Направления обучения", кликнуть "Полный каталог".
2. В появившуюся поисковую строку ввести название профессии.
3. Кликнуть "Найти курс".
4. Кликнуть по нужной профессии из найденных.

### №6
1. В блоке "Направления обучения", кликнуть "Программирование".
2. Выбрать и кликнуть нужную профессию из предложенного списка.

### №7
1. Пролистать страницу до футера(подвала), кликнуть на раздел "Каталог курсов".
2. Выбрать и кликнуть нужную профессию из предложенного списка.

### №8
1. Пролистать страницу до футера(подвала), кликнуть на раздел "Популярные курсы".
2. Выбрать и кликнуть нужную профессию из предложенного списка.

### №9
1. Пролистать страницу до футера(подвала), кликнуть на раздел "Программирование".
2. Выбрать и кликнуть нужную профессию из предложенного списка.

**Ожидаемый результат для всех сценариев:** Находимся на информационной странице выбранной профессии: Тестировщик ПО.
___
## Переход со страницы профессии к анкете записи на курс:
_Предусловие:_ Находимся на информационной странице профессии [Тестировщик ПО](https://netology.ru/programs/qa).

### №10
1. После описания главных преимуществ профессии, никуда не листая, кликнуть кнопку `Записаться`.

### №11
1. Пролистать страницу вниз пока не появится всплывающее окно сверху.
2. На всплывающем окне кликнуть кнопку `Записаться`.

### №12
1. Пролистать всю страницу профессии до формы записи.

**Ожидаемый результат для всех сценариев:** Находимся в той части страницы где прописана стоимость обучения, напротив пустая форма записи на курс.
___
## Заполнение анкеты
_Предусловие:_ Перед нами форма заявки записи на курс.

**Позитивный сценарий:**
- _Имя_: Имя написано на кириллице, от 2-х до 30-и букв, может содержать пробел и дефис. 
- _Телефон_: Начало с +7 по умолчанию, номер должен состояить из 10 цифр. 
- _Электронный адрес_: Написан на латинице, почтовый домен верный (пример: @mail.ru, @yandex.ru, @gmail.com).

### №13
1. Заполнить поле "Имя".
2. Заполнить поле "Телефон".
3. Заполняем поле "Электронный адрес".
4. Кликнуть "Записаться".

**Ожидаемый результат:** Сообщение о том что Заявка записи на курс отправлена.

**Негативные сценарии:**
- Отправка заявки с незаполненными полями:

### №14
1. Пустое поле "Имя".
2. Заполнить поле "Телефон".
3. Заполнить поле "Электронный адрес".
4. Кликуть "Записаться".

### №15
1. Заполнить поле "Имя".
2. Пустое поле "Телефон".
3. Заполнить поле "Электронный адрес".
4. Кликнуть "Записаться".

### №16
1. Заполнить поле "Имя".
2. Заполнить поле "Телефон".
3. Пустое поле "Электронный адрес".
4. Кликнуть "Записаться".

**Ожидаемый результат:** Пустое поле поздсвечено красным,с надписью "Обязательное поле".

- Отправка заявки с невалидными данными: 

### №17
1. Поле "Имя" - ввести одну букву.
2. Заполнить валидными данными поле "Телефон".
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №18
1. Поле "Имя" - ввести больше 30 букв.
2. Заполнить валидными данными поле "Телефон".
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №19
1. Поле "Имя" - ввести цифры.
2. Заполнить валидными данными поле "Телефон".
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №20
1. Поле "Имя" - заполнить латиницей.
2. Заполнить валидными данными поле "Телефон".
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №21
1. Поле "Имя" - Ввести спецсимволы (например: &, $).
2. Заполнить валидными данными поле "Телефон".
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликуть "Записаться".

### №22
1. Заполнить валидными данными поле "Имя".
2. Поле "Телефон" - ввести меньше 10 цифр.
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №23
1. Заполнить валидными данными поле "Имя".
2. Поле "Телефон" - ввести больше 10 цифр.
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №24
1. Заполнить валидными данными поле "Имя".
2. Поле "Телефон" - ввести буквы.
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №25
1. Заполнить валидными данными поле "Имя".
2. Поле "Телефон" - ввести спецсимволы.
3. Заполнить валидными данными поле "Электронный адрес".
4. Кликнуть "Записаться".

### №26
1. Заполнить валидными данными поле "Имя".
2. Заполнить валидными данными поле "Телефон".
3. Поле "Электронный адрес" - ввести больше допустимого количества символов.
4. Кликнуть "Записаться".

### №27
1. Заполнить валидными данными поле "Имя".
2. Заполнить валидными данными поле "Телефон".
3. Поле "Электронный адрес" - ввести данные на кириллице.
4. Кликнуть "Записаться".

### №28
1. Заполнить валидными данными поле "Имя".
2. Заполнить валидными данными поле "Телефон".
3. Поле "Электронный адрес" - ввести адрес без @.
4. Кликнуть "Записаться".

### №29
1. Заполнуть валидными данными поле "Имя".
2. Заполнуть валидными данными поле "Телефон".
3. Поле "Электронный адрес" - ввести больше допустимого количества символов.
4. Кликнуть "Записаться".

**Ожидаемый результат для всех сценариев:** Во всех случаях выводится сообщение о неверно заполненных полях. Запись на курс не произошла.

# 2. Перечень используемых инструментов с обоснованием выбора. 
- IntelliJ IDEA - среда разработки, в которой будем писать автотесты.
- Java 11 - язык программирования, который будет использован для написания автотестов.
- Git и GitHub - инструмент и сервис для управления версиями кода автотестов и предоставления удалённого доступа.
- Postman - для проверки успешных запросов на сервер.
- Selenide - фреймворк для автотестирования GUI.
- Lombok - библиотека для сокращения написания программного кода.
- Faker - библиотека для генерации пользовательских данных которые будут использоваться в автотестировании.
- Allure - фреймворк для создания отчётов о тестировании.

# 3. Перечень необходимых разрешений, данных и доступов.
1. Разрешение на тестирование сайта.
2. Доступ к базе данных.
3. Доступ к API для проверки успешности запросов на сервер.

# 4. Перечень и описание возможных рисков при автоматизации.
1. Автотесты не проверяют UI.
2. Автотетсты нуждаются в поддержании актуальности.

# 5. Перечень необходимых специалистов для автоматизации.
1 инженер по автоматизированному тестированию (QA Automation Engineer).

# 6. Интервальная оценка с учётом рисков в часах.
140-150 часов