<div align="center">

# 📰 Blogicum · шаблоны и маршрутизация

**Первый этап блога на Django: приложения, URL-маршруты, представления и шаблоны**

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-5.1-092E20?logo=django&logoColor=white)
![Tests](https://img.shields.io/badge/pytest-27%2F27_passed-2ea44f?logo=pytest&logoColor=white)

</div>

> Первый этап проекта. Итоговая версия — **[django-sprint4](https://github.com/vadim-guseinov/django-sprint4)**.

## Что сделано

- Два приложения: `blog` (лента, страница поста, категории) и `pages` (статические страницы «О проекте» и «Правила»).
- Маршруты с пространствами имён и параметрами, функции-представления, обработка 404 для несуществующего поста.
- Шаблоны с наследованием от базового, include-фрагменты, Bootstrap.
- **27 из 27 автотестов** проходят.

## Стек

Python 3.12 · Django 5.1 · Django Templates · Bootstrap · pytest

## Запуск

```bash
git clone https://github.com/vadim-guseinov/django-sprint1.git
cd django-sprint1
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt

python -m blogicum.manage runserver
```

Сайт: http://127.0.0.1:8000/

### Тесты

```bash
pytest
```

## Автор

**Вадим Гусейнов** — Python-разработчик (Backend) · [Telegram](https://t.me/eviliing)
