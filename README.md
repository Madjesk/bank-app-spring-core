# Консольное банковское приложение
Этот проект представляет собой консольное банковское приложение, разработанное на языке Java с использованием Spring Framework. Приложение через консольный интерфейс предоставляет функционал управления банковскими счетами пользователей.

**Основные функции:**
- Создание пользователей (USER_CREATE): Возможность регистрации новых пользователей с уникальными логинами.
- Отображение всех пользователей (SHOW_ALL_USERS): Вывод списка всех зарегистрированных пользователей и их счетов.
- Создание счета (ACCOUNT_CREATE): Открытие нового банковского счета для существующего пользователя.
- Пополнение счета (ACCOUNT_DEPOSIT): Пополнение баланса на указанном счете.
- Перевод средств (ACCOUNT_TRANSFER): Перевод средств между счетами, с учетом комиссии для переводов между пользователями.
- Снятие средств (ACCOUNT_WITHDRAW): Снятие средств с указанного счета.
- Закрытие счета (ACCOUNT_CLOSE): Закрытие банковского счета с переводом остатка на другой счет пользователя.
- Сохранение данных в БД: Все данные о пользователях и счетах сохраняются в базе данных, обеспечивая их сохранность при перезапуске приложения.

**Технологии и библиотеки:**
- Java: Основной язык разработки.
- Spring Framework: Используется для управления зависимостями и предоставления базовой функциональности.
- Hibernate: Интеграция для работы с объектно-реляционным отображением (ORM), обеспечивающая сохранение и доступ к данным в базе данных.
- PostgreSQL: Реляционная база данных, используемая для хранения данных приложения.
