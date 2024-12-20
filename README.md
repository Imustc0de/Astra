Астра — это мой первый проект с голосовым управлением, созданный для взаимодействия через голосовые команды. Ассистент находится на стадии разработки, и я открыт для любых советов и идей для улучшения.

Описание проекта
Астра использует аудио-модель VOSK Offline Speech Recognition для обработки голосовых команд. Поскольку возникли трудности при работе со стандартным пакетом, в проекте временно применяется модель Vosk-small-ru.

Основные файлы проекта
words.py
Содержит список доступных команд, которые может выполнять ассистент.

skills.py
Содержит функции, реализующие выполнение команд.

Возможности
На текущем этапе ассистент может:

Выполнять команды, заданные в файле words.py.
Запускать отдельные программы или действия, описанные в skills.py.

Технические особенности
Используется библиотека VOSK для распознавания речи в оффлайн-режиме.
Поддерживается работа с малой моделью (vosk-small-ru), что делает ассистента менее требовательным к ресурсам, но может влиять на точность распознавания.

Требования
Python 3.8+

Установленные зависимости (установка через pip):


pip install vosk sounddevice

Установка и запуск
Клонируйте репозиторий проекта или скачайте файлы.
Установите необходимые зависимости (см. выше).

Запустите главный файл проекта:
main.py

Планы по развитию
Добавить поддержку других моделей VOSK для улучшения распознавания.
Расширить функционал ассистента, добавив больше команд.
Оптимизировать обработку голоса для работы с фоновым шумом.

Помощь в проекте
Проект находится в активной разработке. Если у вас есть идеи, советы или вы хотите предложить помощь, буду рад любой обратной связи!

Контакты
Связаться со мной можно через GitHub или другие указанные контакты.

Если что-то нужно уточнить или добавить, дай знать! 😊
