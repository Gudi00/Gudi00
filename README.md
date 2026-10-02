# Михаил Иоско — Python Backend Developer

Студент 3 курса БГУИР (средний балл за всё время обучения выше 9,5). Пишу асинхронные backend-сервисы на Python: FastAPI, aiogram, SQLAlchemy, PostgreSQL, Docker. В проектах есть миграции, тесты и деплой. Ищу стажировку или позицию Junior Python Backend Developer. Минск, готов обсуждать удалённый формат.

[Почта](mailto:ioskomihailaa@gmail.com) · [Telegram](https://t.me/misha_iosko) · [LinkedIn](https://www.linkedin.com/in/misha-iosko-9ab476440/) · [GitHub](https://github.com/Gudi00)

## Стек

| Область | Технологии |
|---|---|
| Язык | Python 3, SQL, ООП, asyncio |
| Фреймворки | FastAPI, Django, aiogram 3, Pydantic |
| Базы данных | PostgreSQL, SQLite, SQLAlchemy 2.0 (ORM, async), Alembic, Redis |
| Фоновые задачи | Celery, APScheduler |
| Аутентификация | JWT, bcrypt |
| Тестирование | pytest, pytest-asyncio |
| Инфраструктура | Docker, Docker Compose, Linux, Git, деплой на сервер |
| Документация | UML, LaTeX |

## Проекты

Часть репозиториев приватная. Доступ к коду дам по запросу на собеседовании.

**BargainBot** · private · Python, FastAPI, aiogram, PostgreSQL, SQLAlchemy async, Alembic, Docker Compose, pytest
Telegram-бот мониторит объявления на Kufar.by и присылает выгодные. Три основных сервиса: бот, API на FastAPI и PostgreSQL. Уведомления доставляются через очередь в БД с повторными попытками. Покрыт 232 тестами.

**Бот очередей для студенческих групп** · private · aiogram, SQLAlchemy async, SQLite, APScheduler, Docker, pytest
Строит очереди на сдачу лабораторных по расписанию БГУИР (через API iis.bsuir.by), поддерживает 4 режима очереди, обмен местами и уведомления. Развёрнут через Docker и systemd.

**Бот для заказов печати** · private · aiogram, SQLAlchemy, SQLite, PyMuPDF, APScheduler, pytest
Принимает PDF, считает стоимость по числу страниц, ведёт внутренний счёт, скидки и реферальную систему, уведомляет администратора. Использовался для платных заказов печати в общежитии.

**REST API социальной сети** · private · FastAPI, PostgreSQL, SQLAlchemy, Alembic, JWT, Redis, Docker, pytest
Регистрация, вход по JWT, посты, голосования. Refresh-токены хранятся с blacklist в Redis, схема БД версионируется Alembic, есть dev/prod конфигурации Docker Compose. Учебный проект, расширенный сверх курса.

**Сайт мебельного магазина** · [github.com/Gudi00/django](https://github.com/Gudi00/django) · Django, Celery, Redis, Docker
Каталог, профили, заказы, асинхронные и периодические задачи на Celery и Celery Beat.

**Будульники: данные расписаний** · [github.com/Gudi00/budulniki-data](https://github.com/Gudi00/budulniki-data)
Еженедельно собирает расписания всех групп БГУИР из открытого API iis.bsuir.by и публикует сжатый индекс занятости.

## Достижения

- Победитель конкурса на грант Парка высоких технологий для студентов
- Участник хакатонов T1, МТС и БГУИР
- Средний балл за всё время обучения выше 9,5

## Образование

Белорусский государственный университет информатики и радиоэлектроники, факультет информационных технологий и управления, специальность «Автоматизированные системы обработки информации». 2024–2028, сейчас 3 курс.

## Языки

Русский — родной. Английский — B2 (чтение технической документации, переписка).
