## Описание
Этот репозиторий содержит скрипт на Python, выполняющий две задачи параллельно с использованием многозадачности (multiprocessing). Скрипт генерирует случайный пароль и одновременно анализирует два документа Word по следующим задачам:

## Задача 1: Генерация пароля

Функция passw генерирует случайный пароль заданной длины.
Для создания пароля используется набор символов, определенный в переменной mass.
Измеряется время, затраченное на генерацию пароля.

## Задача 2: Сравнение предложений

Функция worker_function2 читает два документа Word (1.docx и 2.docx).
Подсчитывает количество предложений в каждом документе и определяет процент совпадения предложений между ними.
Измеряется время выполнения этой задачи.

## Задача 3: Сравнение слов

Функция worker_function3 также читает эти же документы Word.
Подсчитывает количество слов в каждом документе и определяет процент совпадения слов между ними.
Измеряется время выполнения этой задачи.

## Как использовать
Клонируйте этот репозиторий на свой компьютер:
[git clone](https://github.com/your_username/your_repository.git)
## Установите необходимые зависимости:
- **pip install python-docx**
- **Python 3.7+**

## Запуск
python main.py

## Примечание
Убедитесь, что документы Word (1.docx и 2.docx) находятся в том же каталоге, что и скрипт, перед его запуском.
Не стесняйтесь вносить изменения в скрипт или README в соответствии с вашими конкретными потребностями.
