# 🧪 { Название команды } — URL Shortener 🧪

Это шаблон проекта для курса "Современные методологии и технологии разработки програмного обеспечения". Используйте этот
шаблон для создания ваших репозиториев. Не забудьте дополнить/переписать этот файл, чтобы он соответствовал вашей
работе (хотя бы замените всё в фигурных скобках `{...}` ).

## Команда

- { Фамилия, Имя студента (на русском) } { email } — { имя GitHub аккаунта }
- ...
- { Фамилия, Имя студента (на русском) } { email } — { имя GitHub аккаунта }

## Дизайн документ

В [дизайн документе]({Вставьте сюда ссылку на ваш дизайн-документ --- см. лабораторную работу №1}) описывается
архитектура и детали реализации проекта.

### Структура приложения

Приложение состоит из нескольких модулей

- `auth` **модуль аутентификации** - отвечает за аутентификацию пользователей в системе. Вам необходимо дописать логику
  проверки токена.
- `dto` — содержит описания объектов для передачи данных внутри системы
- `logic` **бизнес логика приложения** — логика сокращения ссылок и др. Необходимо реализовтаь
- `storage` **хранилище данных** — реализация хранилища, которое будет хранить ссылки, пользователей, токены...
  Необходимо реализовать. Обратите внимание, что в рамках этого курса вам нельзя использовать готовые решения, как,
  например, базы даных.
- `views` **REST API** — модуль, в котором находятся все контроллеры приложения. В проекте вы будете использовать
  фреймворк [Micronaut](https://micronaut.io), который упрощает создание REST API.

## Среда разработки

### Java

Проект вы реализуете на языке `Java`, поэтому вам нужно
поставить [JDK](https://ru.wikipedia.org/wiki/Java_Development_Kit) 15. Для установки вы можете использовать:

- [sdkman](https://sdkman.io/) на системах с Linux/MacOS
- [AdoptOpenJDK](https://adoptopenjdk.net/) на ситемах с Windows

### IDE

Для разработки рекомендуется использовать [IntelliJ IDEA Edu](https://www.jetbrains.com/idea-edu/)

### Взаимодействие с REST API

Для взаимодействия с REST API можно использовать следующие инструменты:

- [Postman](https://www.postman.com/downloads/)
- [Insomnia](https://insomnia.rest/) — чуть более простая альтернатива Postman
 
и другие на ваше усмотрение