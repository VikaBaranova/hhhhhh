# Программа для обработки многострочного текста

## Описание

Данная программа считывает многострочный текст, где первая строка содержит имя файла, а остальные строки — его содержимое. Программа выводит имя файла, его содержимое и проверяет, содержится ли в тексте слово "Привет".

## Как работает код

1. **Хранение данных**: 
   - В массиве lines хранятся строки: первая строка — имя файла, остальные строки — его содержимое.

2. **Вывод имени файла**: 
   - С помощью функции printf выводится имя файла.

3. **Объединение содержимого**:
   - Содержимое объединяется в одну строку content, добавляя переносы строк между ними.

4. **Вывод содержимого**:
   - Содержимое файла выводится на экран.

5. **Поиск слова "Привет"**:
   - Программа реализует простой алгоритм поиска подстроки (в данном случае "Привет") в строке content. Если слово найдено, выводится соответствующее сообщение.

## Запуск программы

Для компиляции и запуска программы используйте следующие команды:

