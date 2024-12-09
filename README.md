# risks-analization-application

# Проектная деятельность I семестр 2024-2025 учебного года

# Настройка проекта

## Создать виртуальную среду Python. Рекомендуемые версии Python 3.10-3.12.
- Открыть папку проекта в командной строке
- Ввести команду `"%localappdata%\Programs\Python\Python310\python" -m venv venv`
> [!IMPORTANT]  
> Вместо Python310 может быть другая версия, установленная в вашей системе, например версия 3.10 будет являться 310, 3.11 - 311 и т.д.

## Переключиться в созданную виртуальную среду
- Открыть папку проекта в командной строке
- Ввести команду `venv\scripts\activate`
- После введения команды должно появиться выражение (venv)

## Установка пакетов
- Переключиться в созданную виртуальную среду (см. пункт выше)
- Ввести команду `pip -r requirements.txt`, это установит все требуемые пакеты приложения

# Запуск приложения
- Переключиться в созданную виртуальную среду (см. пункт выше), а также убедиться что все пакеты установлены.
- Ввести команду `python src\script.py`
