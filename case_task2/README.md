# Веб-приложение “Книжный магазин” BookStore на Next.js с MongoDB и NextAuth

Данный проект представляет собой веб-приложение “Книжный магазин”, который разработан с использованием фреймворка Next.js версии 14 и базы данных MongoDB с помощью MongoDB Compass.

## Выполненные задачи

Создать Web-версию книжного магазина;

1. Необходимо создать web-страницу;
2. Создать 2 интерфейса: администратора и пользователя;
3. Создать базу данных Ваших любимых книг;
4. Для пользовательского интерфейса добавить возможность просмотра книги из библиотеки;
5. Добавить возможность сортировки на основе:

- Категории;
- Автора;
- Года написания;

➔ Добавить функцию покупки или аренды книги сроком на 2 недели / месяц / 3 месяца;

➔ Для администратора добавить возможность изменения списка книг , управления ценой, статусы книг и их доступность, возможность напоминать пользователям об окончании срока аренды (автоматически);

## Установка

Следуйте этим шагам, чтобы запустить проект локально:

1. **Склонируйте репозиторий на свой компьютер**

2. **Настройте переменные окружения:**

Создайте файл .env на основе .env.example и запишите в него адрес для подключения к базе данных и токен для NextAuth. Пример:

```bash
MONGODB_URI=mongodb://127.0.0.1/blog
NEXTAUTH_SECRET=my_secret_token
```

3. **Установите зависимости:**

```bash
npm install
```

4. **Запустите проект:**

```bash
npm run dev
```

5. **Откройте браузер и перейдите по адресу:**

http://localhost:3000.

## Использование

### Регистрация администратора

Регистрация администратора проходит по секретному пути http://localhost:3000/register/admin.

### Создание библиотеки ваших книг

После регистрации и авторизации администратора можно в админ панели добавлять книги в базу данных.
