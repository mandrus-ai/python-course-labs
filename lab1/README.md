[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mandrus-ai/python-course-labs/blob/main/lab1/notebooks/lab1.ipynb)

# Практическое занятие 1. Рабочее окружение

Автор: Мандрусенко Андрей Валерьевич, группа 251-952

## Структура папки lab1

Папка data содержит данные, папка notebooks – ноутбук lab1.ipynb, файл requirements.txt – список библиотек.

## Запуск на локальном компьютере

В папке lab1:

1. Создать окружение: python -m venv .venv
2. Включить окружение: .venv\Scripts\activate (macOS и Linux: source .venv/bin/activate)
3. Установить библиотеки: pip install -r requirements.txt
4. Открыть notebooks/lab1.ipynb в VS Code и выбрать ядро .venv

## Сравнение сред

| | Локально | Colab |
|---|---|---|
| Python | 3.12.10 | 3.13.18 |
| pandas | 3.1.1 | 2.2.3 |
| Файлы | На компьютере | Во временной среде |
| Запуск | Python, VS Code, библиотеки | Браузер и аккаунт Google |

