**Домашнє завдання #10**

У минулій домашній роботі ви виконували скрапінг сайту http://quotes.toscrape.com.

Вам необхідно самостійно реалізувати аналог такого сайту на Django.

- Реалізуйте можливість реєстрації на сайті та вхід на сайт.
- Можливість додавання нового автора на сайт лише для зареєстрованого користувача.
- Можливість додавання нової цитати на сайт із зазначенням автора тільки для зареєстрованого користувача.
- иконайте міграцію бази даних із MongoDB, яка у вас є, у Postgres для вашого сайту. Можна реалізувати кастомним скриптом. (За бажанням можете залишити та працювати з цитатами та авторами в MongoDB, а з користувачами у Postgres)
- Можна зайти на сторінку кожного автора без автентифікації користувача
- Усі цитати доступні для перегляду без автентифікації користувача

**Додаткова частина**

- Реалізуйте пошук цитат за тегами. При натисканні на тег, виводиться список цитат з цим тегом.
- Реалізуйте блок "Top Ten tags" та виведення найпопулярніших тегів.
- Реалізуйте пагінацію. Це кнопки next та previous
- Замість перенесення даних з бази даних MongoDB, реалізуйте можливість скрапінгу даних прямо з вашого сайту по натисканню певної кнопки на формі та наповнення бази даних сайту.
