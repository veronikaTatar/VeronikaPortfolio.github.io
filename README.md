# VeronikaPortfolio.github.io
**Контакты**
[![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github)](https://github.com/veronikaTatar)
[![Email](https://img.shields.io/badge/-Email-D14836?logo=gmail&logoColor=white)](veronik4578@gmail.com)
[![Linkedin](https://img.shields.io/badge/-Linkedin-26A5E4?logo=linkedin&logoColor=white)](www.linkedin.com/in/tatarchukveronika)
---

## Технологии и навыки
**Языки программирования:**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Backend & Фреймворки:**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?logo=hibernate&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)

базовые навыки:
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework-512BD4?logo=dotnet&logoColor=white)  

**Базы данных:**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-000000?logo=sqlalchemy&logoColor=white)  

**Инструменты и платформы:**
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?logo=apachemaven&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)

**Тестирование:**
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?logo=&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?logo=pytest&logoColor=white)
![Unittest](https://img.shields.io/badge/Unittest-FF6C37?logo=python&logoColor=white)   

---

## Проекты  

<details open>
<summary><b>🐍 Python-проекты</b> </summary>

<br>

### QRKot: Фонд поддержки котов (https://github.com/veronikaTatar/QRkot-spreadsheets)
**Стек:** `Python`, `FastAPI`, `SQLAlchemy`, `PostgreSQL`, `AIOHTTP`, `Pydantic`, `JWT`, `FastAPI Users`, `XLSXWriter`, `Yandex Disk API`

**Описание:**  
QRKot — это веб-приложение для благотворительного фонда поддержки котов, позволяющее создавать целевые проекты (сборы средств на конкретные задачи) и принимать пожертвования. Пожертвования автоматически распределяются между открытыми проектами: средства направляются в самый "старый" проект, который ещё не собрал нужную сумму. Система поддерживает мультиролевую модель (Анонимный пользователь, Зарегистрированный пользователь, Суперпользователь).  
Интеграция с Яндекс Диском для формирования и публикации Excel-отчётов о скорости закрытия проектов.  

**В ходе работы над проектом было сделано:**
- создан API-сервис на базе FastAPI с асинхронной архитектурой;
- реализована автоматическая система распределения пожертвований между открытыми проектами с использованием единой транзакции;
- реализована интеграция с Яндекс Диском для генерации Excel-отчётов о скорости закрытия проектов;
- закреплены на практике основы асинхронного программирования и работы с внешними API.
---

### Foodgram: сервис для публикации рецептов (https://github.com/veronikaTatar/foodgram)
**Стек:** `Python`, `Django`, `YAML`, `Nginx`, `Gunicorn`, `React`, `Docker`, `PostgreSQL`, `Postman`

**Описание:**  
Foodgram — это сайт, на котором пользователи могут публиковать свои рецепты, добавлять чужие рецепты в избранное  
и подписываться на публикации других авторов.  

**В ходе работы над проектом было сделано:**
- создан API-сервис на базе проекта Django;
- подключено SPA к бэкенду на Django через API;
- создано, развёрнуто и запущено на сервере мультиконтейнерное приложение;
- закреплены на практике основы DevOps, включая CI/CD.
---  

### BlogDjango: веб-платформа для ведения блогов (https://github.com/veronikaTatar/BlogDjango)  
**Стек:** `Python`, `Django`, `Django ORM`, `HTML/CSS`, `Bootstrap`, `Django Templates`, `Django Authentication System`

**Описание:**  
Полнофункциональная веб-платформа для ведения блогов с системой аутентификации пользователей, публикацией постов, категоризацией и пагинацией. Проект реализован на Django с использованием встроенных механизмов безопасности и шаблонизации.

**Ключевые особенности:**
- **MVT (Model-View-Template):** Стандартная архитектура Django
- **Система аутентификации:** Полный цикл регистрации, входа, смены и восстановления пароля через встроенные представления Django
- **Шаблонизация:** Использование наследования шаблонов (base.html), включений (includes) и тегов Django Bootstrap
- **Безопасность:** CSRF-защита, безопасная обработка форм, защищённые маршруты
- **Пагинация:** Разбивка списка постов на страницы для удобства навигации
- **Bootstrap Integration:** Использование `django-bootstrap5` для стилизации форм
---

### YaNote & YaNews: Django-приложения с комбинированной системой тестирования (https://github.com/veronikaTatar/django-testing)
**Стек:** `Python`, `Django`, `Django ORM`, `pytest`, `unittest`, `Django Test Client`, `Class-Based Views`

**Описание:**  
Два полноценных Django-приложения с комплексной системой тестирования, демонстрирующих два подхода к тестированию в одном проекте.  
YaNote — система управления персональными заметками с автогенерацией slug из русского текста.  
YaNews — новостной агрегатор с ролевой моделью доступа и безопасностью на уровне представлений.

**Ключевые особенности:**
- **Гибридная система тестирования**: Использование как `unittest` (встроенного в Django), так и `pytest` с фикстурами
- **Полное покрытие тестами**: 
  - `unittest.TestCase` для тестирования логики, маршрутов и содержимого
  - `pytest` для параметризованных тестов и фикстур
- **Автогенерация slug**: Автоматическое транслитерирование русских заголовков в уникальные URL с помощью `pytils`
- **Безопасность доступа**: Тестирование разграничения прав (автор vs читатель vs аноним) через `LoginRequiredMixin`
- **Class-Based Views**: Тестирование всех стандартных CBV (Create, Update, Delete, Detail, List)
- **Тестирование маршрутов**: Полная проверка доступности эндпоинтов для разных типов пользователей
- **Тестирование контекста**: Проверка передачи правильных форм и объектов в шаблоны
---

</details>

<details open>
<summary><b>☕ Java-проекты</b> </summary>

<br>

### ContentMarketing: Система контент-маркетинга с модулем планирования публикаций и анализа эффективности контента (https://github.com/veronikaTatar/ContentMarketingBackend)
**Стек:** `Java 21`, `Spring Boot `, `Spring Data JPA`, `PostgreSQL`, `React 18`, `React`, `TypeScript`, `Vite`, `JWT`, `OAuth 2.`, `REST API`

**Описание:**  
Веб-приложение для автоматизации процессов контент-маркетинга.
Мультиролевая система (Администратор, Контент-менеджер, Автор). Интеграция с внешними сервисами (Telegram, Discord) для автоматической публикации контента и сбора статистики. Аутентификация через GitHub OAuth 2.0. Генерация отчетов о нагрузке сотрудников и эффективности контента в Excel файл.  

**Многоуровневая архитектура:**
- **Presentation Layer**: REST-контроллеры Spring MVC, валидация через @Valid и Jakarta Bean Validation
- **Application Layer**: Сервисы (@Service) с реализацией бизнес-логики и паттернами Command, Observer, Strategy
- **Persistence Layer**: Spring Data JPA репозитории, Hibernate ORM, миграции через Flyway
- **Security Layer**: JWT-аутентификация (access + refresh токены), ролевая модель (RBAC), BCrypt хеширование паролей, OAuth 2.0 / OpenID Connect через GitHub
- **Client Layer**: React SPA с TypeScript, Redux Toolkit, Axios, адаптивный дизайн
- **Интеграция**: REST API Telegram и Discord для публикации контента, GitHub API для аутентификации
- **Аналитика**: Расчет метрик вовлеченности (ER, ERR, охват, виральность), сравнение с целевыми KPI
- **Документирование API**: SpringDoc OpenAPI 3 (Swagger UI)
---

### CinemaFocus: Web-приложение для кинотеатра (https://github.com/veronikaTatar/Web-cinema)
**Стек:** `Java`, `JSP`, `Servlets`, `Hibernate`, `PostgreSQL`, `Bootstrap`, `MVC Architecture`

**Описание:**  
Полнофункциональное веб-приложение для управления кинотеатром с системой онлайн-бронирования билетов. Мультиролевая система (Гость, Пользователь, Сотрудник, Администратор).Система рейтингов и отзывов для кинозалов. Вывод отчета о нагрузке кинотеатра в Exscel файл.

**Многоуровневая архитектура:**
- **Presentation Layer**: JSP с JSTL, Bootstrap для адаптивного дизайна
- **Controller Layer**: Java Servlets (MVC паттерн)
- **Service Layer**: Бизнес-логика приложения
- **DAO Layer**: Data Access Objects с Hibernate ORM
- **Database Layer**: PostgreSQL с реляционной схемой
- **Отчетность**: генерация Excel отчетов через Apache POI
---

### Beauty Salon Management System - GUI приложение (https://github.com/veronikaTatar/beaitySalon-client-server-)
**Стек:** `Java`, `JavaFX`, `JDBC`, `SQL`, `TCP/IP`, `Multithreading`

**Описание:**  
Информационная система для управления косметическим салоном с мониторингом нагрузки сотрудников. Приложение использует клиент-серверную архитектуру с многопоточным сервером.

**Ключевые особенности:**
- **Клиент-серверная архитектура**: TCP/IP протокол, многопоточный сервер
- **Безопасность**: TLS 1.2+ шифрование соединений
- **GUI**: JavaFX с FXML (Scene Builder), Model-View-Controller паттерн
- **Работа с данными**: JDBC для работы с БД, валидация ввода (RegEx)
- **Отчетность**: генерация CSV отчетов через OpenCSV
- **Паттерны**: Singleton, Abstract Factory, MVC
---

### Condorcet: Система управления пассажирскими перевозками JavaFX GUI 
сервер (https://github.com/veronikaTatar/flight_monitoring_server)
клиент (https://github.com/veronikaTatar/flight_monitoring_client)

**Стек:** `Java`, `JavaFX`, `Hibernate (JPA)`, `MySQL`, `TCP/IP`, `Многопоточность`

**Описание:**  
Корпоративная клиент-серверная система для управления данными пассажирских перевозок с использованием TCP-протокола и реляционной базы данных. Проект демонстрирует архитектурные принципы построения распределенных приложений на Java.

**Ключевые особенности:**
- **Клиент-серверная архитектура**: TCP/IP протокол с многопоточным сервером для обработки запросов
- **ORM маппинг**: Hibernate JPA для работы с MySQL, аннотации для конфигурации сущностей
- **JavaFX GUI**: Современный интерфейс с FXML, паттерн Model-View-Controller
- **Связи сущностей**: OneToMany/ManyToOne отношения между PersonData, User и Passenger
- **Безопасность**: Хэширование паролей, валидация ввода, ролевая модель доступа

**Архитектурные решения:**
- **Трехуровневая архитектура**: Разделение на клиент, сервер и слой данных
- **Singleton паттерн**: Для управления TCP-соединениями (ClientSocket)
- **Lazy/Eager Loading**: Оптимизация загрузки данных через стратегии Hibernate
---

</details>

<details open>
<summary><b>🚀 Другие проекты</b> </summary>

<br>

### TaskFlow: Мобильное приложение управления задачами Flutter + Firebase (https://github.com/veronikaTatar/Tasks_app)
**Стек:** `Flutter`, `Dart`, `Firebase`, `Firestore`, `FCM (Push-уведомления)`

**Описание:** 
Полнофункциональное мобильное приложение для управления задачами с серверной частью на Firebase. Приложение демонстрирует современный подход к разработке кроссплатформенных приложений с использованием облачных сервисов. Поддерживает обновления через StreamBuilder.
 
**Архитектурные паттерны:**
- **Архитектура**: Четкое разделение на слои (Presentation, Domain, Data)
- **Паттерн Команда**: Инкапсуляция бизнес-логики в отдельных командах
- **Dependency Injection**: Внедрение зависимостей для тестируемости
- **Model-View-Controller (MVC)**: Организация пользовательского интерфейса
---

### Классическая игра "Змейка" на Pygame (https://github.com/veronikaTatar/the_snake)
**Стек:** `Python`, `Pygame`, `OOP`, `Type Hints`

**Описание:**  
Классическая аркадная игра "Змейка" с современной объектно-ориентированной архитектурой. Проект демонстрирует применение принципов чистого кода и модульного проектирования в игровой разработке. Вывод отчета о нагрузке салона в СМЫ файл.

**Ключевые особенности:**
- **Объектно-ориентированный дизайн**: Четкое разделение ответственности между классами (GameObject, Snake, Apple)
- **Система типов**: Полное использование Type Hints (аннотации типов) для повышения надежности кода
- **Модульная архитектура**: Каждый компонент игры инкапсулирован в отдельном классе
- **Гибкая настройка**: Константы для легкой кастомизации (цвета, размеры, скорость)
- **Коллизии и логика**: Определение столкновений с яблоком и самим собой
---

### Car Верстка для Web-приложения аренды автомобилей (https://github.com/veronikaTatar/cars)

**Стек:** `Angular`, `TypeScript`, `RxJS`

**Описание:**  
Полнофункциональный сайт для аренды  автомобилей с динамической фильтрацией по маркам, интерактивной формой бронирования. 

**Ключевые особенности:**
- **Динамическая фильтрация**: Reactivity-based фильтрация по маркам автомобилей
- **REST API интеграция**: Загрузка данных об автомобилях и отправка заявок через HTTP Client
- Адаптивная верстка с использованием CSS Grid/Flexbox
- Управление асинхронными операциями и детекцией изменений (Zone.js)
  
</details>

**С другими проектами можнно ознакомится в профиле**


