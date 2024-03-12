# goit-js-hw-05
* принцип роботи колбек-функцій та стрілочних функцій;
* растосовувати цих функцій на практиці;
* як працювати з масивом об'єктів;
* методи масивів, як: forEach, map, flatMap, filter, find і every, some, reduce, toSorted;
* налаштування свого порядку сортування чисел та рядків;
* використання методів масиву у ланцюжках;

      Задача 1. Імена користувачів.
Напиши стрілочну функцію getUserNames(users), яка прийматиме один параметр users — масив об’єктів користувачів. Функція має повертати масив імен усіх користувачів (властивість name) із масиву users.

      Задача 2. Користувачі з другом.
Напиши стрілочну функцію getUsersWithFriend(users, friendName), яка прийматиме два параметра:
* перший параметр users — масив об’єктів користувачів
* другий параметр friendName — ім’я друга для пошуку.
Функція має повертати масив усіх користувачів із масиву users, у яких є друг з іменем friendName.

Друзі кожного користувача зберігаються у властивості friends.
Якщо користувачів, у яких є такий других немає, то функція має повернути порожній масив.

        ! Поради:
  Метод filter() можна використовувати для створення нового масиву з елементами, які задовольняють певну умову.
    Використовуй метод includes() для перевірки, чи масив friends містить friendName.

      Задача 3. Сортування за кількістю друзів.
Напиши стрілочну функцію sortByDescendingFriendCount(users) , яка прийматиме один параметр users — масив об’єктів користувачів.

Функція має повертати масив усіх користувачів, відсортованих за спаданням кількостій їх друзів (властивість friends).

      Задача 4. Загальний баланс
Напиши стрілочну функцію getTotalBalanceByGender(users, gender), яка прийматиме два параметра:
  * перший параметр users — масив об’єктів користувачів,
  * другий параметр gender — рядок, що зберігає стать.
Функція має використовувати ланцюжок виклику методів та повертати загальний баланс користувачів (властивість balance), стать яких (властивість gender) збігається зі значенням параметра gender.
