# second_hw_de_course2025_misis
   Второе ДЗ на курсе по Инженирингу данных от ITam | HDFS + MapReduce

# Домашнее Задание 2 : Работа с hdfs и map reduce

## Полезные ссылки:

- Книга о Hadoop (объяснение Map Reduce на странице 19) - [[Ссылка](https://hadoop.apache.org/docs/r2.4.1/hadoop-project-dist/hadoop-common/FileSystemShell.html)]
- Пример конфигурации для стадий перемешивания и сортировки в Map Reduce - [[Ссылка](https://hadoop.apache.org/docs/current/hadoop-streaming/HadoopStreaming.html#More_Usage_Examples)]
- Основные команды HDFS - [[Ссылка](https://hadoop.apache.org/docs/r2.4.1/hadoop-project-dist/hadoop-common/FileSystemShell.html)]

## Задание 1:

Подсчитать количество слов в первом тексте с помощью фреймворка Map-Reduce:

1. В соответствующей ячейке реализовать код шага Map
2. В ячейке ниже реализовать код шага Reduce
3. Выполнить ячейку с bash-командой для локальной самопроверки
4. Запустить bash-скрипт для запуска MR-таска
5. Логи выполнения ячеек должны быть видимы
   
Важно: подсчитывайте число только тех слов, длина которых больше 4 символов.
Проводить процесс удаления знаков препинания и прочих символов не нужно

## Задание 2:

Выведите топ-5 наиболее посещаемых сайтов за каждую из дат, представленных в файле "Посещения сайтов". Реализуйте код для этапов Map и Reduce. Кроме того, нужно сделать следующее:

1. Разместите это в ячейках с помощью магической функции %%writefile.
2. Напишите команду запуска MapReduce в отдельной ячейке, аналогичной заданию 2.1 (скопируйте и добавьте параметры конфигурации, если это необходимо).
3. Логи выполнения ячейки должны быть видимы.

Также рассмотрите обработку исключений при обработке звонков и сохранение в лог-файлах.

## Важное замечание:

Программы Map и Reduce должны работать с памятью сложности O (1), и если вы собираетесь создать список данных, то он не должен быть размера O (n).

## Формат сдачи

Необходимо отправить jupyter-ноутбук с кодом и логами выполнения ячейки. Вы также можете добавить дополнительные комментарии в сам блокнот.
Пожалуйста, убедитесь, что предоставленные ссылки работают и доступны для загрузки.
