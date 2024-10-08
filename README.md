# Скачать видео с GetCourse.ru

> Текущий скрипт использует только возможности **bash**.

Скрипт анализирует HTML-страницу с видеороликами курса, чтобы обнаружить все ссылки на видео-плееры. Затем он пытается скачать и сохранить каждый найденный ролик рядом с собой под указанным именем.

## Использование

Для использования скрипта необходимо выполнить следующие шаги:
1. Скачать скрипт [getcourse-download.sh](./getcourse-download.sh) на локальный компьютер
2. Добавить права на выполнение скрипта по необходимости

```bash
sudo chmod ug+x getcourse-download.sh
```

3. Зайти на страницу с видеороликом курса и сохранить только HTML-страницу
   - Открыть контекстное меню правой кнопкой мыши
   - Найти и выбрать пункт _Сохранить как_
   - Выбрать _HTML only_ из списка _Тип файла_
   - Сохранить файл в любое место или рядом со скриптом
4. Запустите скрипт и следуйте инструкциям его выполнения
