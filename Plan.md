# План тестирования
### Перечень автоматизируемых сценариев
  - [ ] Оплата тура картой со статусом “APPROVED” (кредитная и дебетовая)
  - [ ] Оплата тура картой со статусом "DECLINED" (кредитная и дебетовая)
  - [ ] Оплата тура картой с незарегистрированным номером
  - [ ] Отправка пустой формы
  - [ ] Валидация данных в поле "Номер карты"
  - [ ] Валидация данных в поле “Месяц”
  - [ ] Валидация данных в поле “Год”
  - [ ] Валидация данных в поле “Владелец”
  - [ ] Валидация данных в поле “CVC/CVV”
  - [ ] Отправка запроса на оплату тура по дебетовой карте со статусом “APPROVED”
  - [ ] Отправка запроса на оплату тура по кредитной карте со статусом “APPROVED”
  - [ ] Отправка запроса на оплату тура по дебетовой карте со статусом "DECLINED"
  - [ ] Отправка запроса на оплату тура по кредитной карте со статусом "DECLINED"
### Перечень используемых инструментов
- **IntelliJ IDEA** среда разработки
- **Java** язык программирования
- **Junit5** фреймворк для тестирования
- **Selenide** инструмент для автоматизации
- **Docker** для работы с СУБД
- **Allure** для создания отчетов по итогу тестирования
 ### Перечень и описание возможных рисков при автоматизации
- Нет полноценных требований к продукту.
- Отсутствие тестовых меток. Сложно поддерживать тесты.
 ### Интервальная оценка с учётом рисков в часах
- Планирование тестирования (12 часов)
- Подготовка окружения к тестированию (5 часов)
- Ручное тестирование (6 часов)
- Написание автотестов (72 часа)
- Заведение баг репортов (12 часов)
- Составление отчетности (8 часов)
 ### План сдачи работ
- Планирование (3 дня 31.05 )
- Написание и прогон автотестов (10 дней 10.06)
- Заведение баг репортов (2 дня 12.06)
- Составление отчетности (2 дня 14.06)
