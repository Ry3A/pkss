# pkss
**Диаграмма структуры функциональных возможностей (mindmap)**
```mermaid
mindmap
  root(DnD Помощник)
    Пользователи
      Регистрация
      Авторизация
      Управление профилем
    Персонажи
      Создание
      Редактирование
      Удаление
      Просмотр характеристик
    Кампании
      Создание кампании
      Управление игроками
      Отслеживание прогресса
    Заклинания и Предметы
      Библиотека заклинаний
      Поиск и фильтрация
      Добавление новых предметов
    Автоматизация
      Расчеты характеристик
      Броски кубиков
      Генерация листов персонажей
    Платформы
      Веб-версия
      Мобильное приложение

```
На диаграмме представлены основные функции системы.
**Диаграмма путешествия пользователя (user jorney)**
```mermaid
journey
  title Путешествие пользователя в "DnD помощник"
  section Регистрация и вход
    Пользователь: 5: Регистрация
    Пользователь: 4: Вход в систему
  section Работа с персонажами
    Пользователь: 4: Создание нового персонажа
    Пользователь: 3: Редактирование характеристик
    Пользователь: 4: Просмотр листа персонажа
  section Управление кампаниями
    Пользователь: 3: Создание новой кампании
    Пользователь: 4: Добавление игроков
    Пользователь: 3: Отслеживание событий
  section Библиотека заклинаний
    Пользователь: 4: Поиск заклинаний
    Пользователь: 5: Добавление нового заклинания
```
Диаграмма описывает состояние пользователя при взаимодействии с системой, с разными её частями и функциями.
**Диаграмма квадрант-граф**
```mermaid
quadrantChart
    title Функциональности приложения "DnD помощник"
    x-axis Легкость реализации --> Высокая сложность
    y-axis Низкая важность --> Высокая важность
    "Автоматизация расчетов": [0.7, 0.9]
    "Управление кампаниями": [0.8, 0.8]
    "Библиотека заклинаний": [0.6, 0.7]
    "Мобильное приложение": [0.9, 0.6]
    "Генерация персонажей": [0.4, 0.8]
```
Диаграмма описывает важность разработки тех или иных функций на основе приоритета и сложности реализации.
**Диаграмма git graph**
```mermaid
gitGraph
    commit id: "Начало проекта"
    branch feature/characters
    checkout feature/characters
    commit id: "Добавлена функциональность персонажей"
    checkout main
    merge feature/characters id: "Слияние функциональности персонажей"
    branch feature/campaigns
    checkout feature/campaigns
    commit id: "Добавлено управление кампаниями"
    checkout main
    merge feature/campaigns id: "Слияние управления кампаниями"
    branch feature/spells
    checkout feature/spells
    commit id: "Реализована библиотека заклинаний"
    checkout main
    merge feature/spells id: "Слияние библиотеки заклинаний"
```
Описывает дерево коммитов (пример) в удобном формате.
