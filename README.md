# Практическое занятие 1
# Шишков Алексей Дмитриевич ЭФМО-02-21

Цель работы
Развернуть рабочее окружение Go на Windows, создать минимальный HTTP-сервис на net/http, подключить и использовать внешнюю зависимость, собрать и проверить приложение.

Задание:

Установить Go и Git, проверить версии.
Инициализировать модуль Go в новом проекте.
Реализовать HTTP-сервер с маршрутами /hello (текст) и /user (JSON).
Подключить внешнюю библиотеку (генерация UUID) и использовать её в /user.
Запустить и проверить ответы curl/браузером.
Собрать бинарник .exe и подготовить README и отчёт.
# Запуск

Зайти в папку /helloapi и выполнить go run ./cmd/server
# Структура проекта:
helloapi/
│  go.mod
│  go.sum
│  README.md
│  .gitignore
│
└─ cmd/
   └─ server/
      └─ main.go
# Выполнение запросов
<img width="1187" height="299" alt="изображение" src="https://github.com/user-attachments/assets/98695f9e-2ea5-4c3b-84c2-0f892cb039da" />

<img width="1262" height="324" alt="изображение" src="https://github.com/user-attachments/assets/bb856bfa-d0c7-4d0d-8215-182885bf9f76" />
<img width="1375" height="389" alt="изображение" src="https://github.com/user-attachments/assets/f8ab6b5f-96bb-46e8-8182-9e9b4e9a5c07" />




