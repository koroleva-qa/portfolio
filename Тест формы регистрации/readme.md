# Исследовательское тестирование	

### Цель исследования:	
Провести исследовательское тестирование функционала регистрации на сайте

### Объект тестирования:	
Интерфейсная часть формы регистрации сайта www.exist.ru

### Задачи:	
- Описать проверку функционала регистрации в формате чек-листа и тест-кейсов
- Протестировать интерфейс
- Написать отчет о проделанной работе
- Найденные ошибки описать в отчете
   
### Сроки тестирования:
27.06.2024 - 03.07.2024

### Окружение:	
Windows 10 Version 22H2, Яндекс.Браузер 24.4.5.498 (64-bit), 1920х1080

### Распределение результатов теста:
![image](https://github.com/koroleva-qa/portfolio/assets/174460709/952492c0-b5da-45bf-996c-8000aedf4b26)

### Обнаруженные проблемы:	
Тест-кейс: TC3 Иконка флага соответствует выбранной стране
Багрепорт: https://tracker.yandex.ru/BUG-981

1. При выборе страны "Германия" отображает иконку флага России
2. При выборе страны "Грузия" отображает иконку со старым флагом Грузии

Приоритет - низкий
Исправление можно заложить в следующий билд

### Положительные результаты:	
Остальные аспекты интерфейса формы регистрации работают согласно документации

### Выводы:	
Интерфейсная часть формы регистрации прошла проверку по функционалу.
Обнаружены некритичные ошибки срабатывания иконок флагов для списка стран, которые можно починить в следующем билде. Далее переходим к тестам ввода

### Рекомендации:	
Перед починкой бага требуется решение аналитика: вероятно изначально лучше пересмотреть список и убрать ненужные страны, чем чинить то, что не используется пользователями и не имеет практического смысла



