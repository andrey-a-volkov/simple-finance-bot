# simple-finance-bot

### 1. Цель проекта

Создать телеграмм бота для мониторинга ежедневных трат и планирования бюджета. Бот будет основным инструментом для контроля финансов (вне биржи). 
### 2. Описание системы
   1. Бот должен находиться на облачном сервере. Таком как `cloud.yandex.ru`  или другом и быть в доступе постоянно
   2. Взаимодействие с ботом происходит в телеграмм чате.
   3. Так же возможно написать кнопки меню для выбора категории трат и удобного (быстрого) добавления трат
   4. Взаимодействие с google таблицами для создания отчетов
### 3. Функционал
   1. Показать категории 
   2. Добавить расход
   3. Показать последние 5 трат
   4. Показать траты за последнюю неделю
   5. Показать остаток лимита
   6. Вывести отчет за месяц (по категориям)
   7. Удалить запись
   8. Вывести отчет в виде графика (google таблица)
### 4. Стек технологий
   1. Python
   2. SqlAlchemy
   3. iogram
   4. Google sheets
   5. Docker 