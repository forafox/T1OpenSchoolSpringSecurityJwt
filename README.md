# Реализация аутентификации и авторизации с использованием Spring Security и JWT

## Описание:

Рабочее веб-приложение с базовой аутентификацией и авторизацией на основе Spring Security и JWT,
сопровождаемое модульными тестами и краткой документацией к API.

## Выполненные требования:

### Настройка конфигурации безопасности:

1. Настроена базовая конфигурация Spring Security.
2. Используется JWT для аутентификаци пользователей.
3. Сдайте класс для генерации и проверки JWT токенов.

### Реализация контроллеров:

1. Созданы контроллеры для аутентификации и регистрации пользователей.
2. Реализованны методы для создания нового пользователя и генерации JWT токена при успешной аутентификации.
3. Реализованно сохранение пользователей в базу данных PostgreSQL.
4. Добавлена поддержка ролей пользователей и настроена авторизация на основе ролей.

### Тестирование

- Написаны модульные тесты для контроллеров и сервисов.

### Документация

- Добавлена краткая документация к API с использованием Swagger.

## Стек

- Java
- Spring Boot
- Gradle
- PostgreSQL

## Особенности

- Документация к API.(Интерактивная и api-docs.json)
- Для приложения разработана инструкция по сборке. Сборка выполняется с помощью Docker.
- Присутствует файл .env. Представленные данные являются публичными и используются только! при тестировании.

## Ссылки (Доступны во время работы приложения)

- Интерактивная Swagger документация (http://localhost:8080/swagger-ui/index.html#/)

## Сборка

Для сборки приложения необходимо выполнить следующие действия.

1. Склонировать репозиторий:

   ```bash
   git clone https://github.com/forafox/T1OpenSchoolSpringSecurityJwt
   cd T1OpenSchoolSpringSecurityJwt
   ```

2. Выполнить build в директории приложения с помощью следующей команды:

   ```bash
   docker compose build 
   ```
3. Для запуска приложения необходимо выполнить следующую команду:

   ```bash
   docker compose up
   ```

- Пункты 3 и 4 **можно** объединить в следующую команду:

    ```bash
    docker compose up --build
    ```
  