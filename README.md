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
    title Development Priorities
    x-axis Low Priority --> High Priority
    y-axis Low Complexity --> High Complexity
    quadrant-1 High Priority
    quadrant-2 Requires Analysis
    quadrant-3 Re-evaluate
    quadrant-4 Can Be Improved
    Authorization and Profile Management: [0.3, 0.7]
    Character Creation: [0.8, 0.4]
    Spell Library: [0.7, 0.6]
    Campaign Management: [0.8, 0.8]
    Automated Calculations: [0.6, 0.9]
    Inventory Management: [0.5, 0.5]
    Random Event Generator: [0.4, 0.4]
    Mobile Compatibility: [0.9, 0.6]
    Integration with Discord: [0.7, 0.3]
    Advanced NPC Customization: [0.4, 0.8]

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
