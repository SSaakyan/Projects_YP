# Анализ взаимодействия пользователей с карточками Яндекс.Дзен

**Цель исследования:**
построить дашборд для ответа на вопросы:  
- Сколько взаимодействий пользователей с карточками происходит в системе с разбивкой по темам карточек?
- Как много карточек генерируют источники с разными темами?
- Как соотносятся темы карточек и темы источников?

Дашборд основывается на пайплайне, который будет брать данные из таблицы, в которых хранятся сырые данные, 
трансформировать данные и укладывать их в агрегирующую таблицу. Пайплайн разработан дата-инженерами.

## Стек

Python, PostgreSQL, dash, Tableau
